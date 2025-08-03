# Amplitude Modulation





## JSFX Plugin

```
desc:Balanced Amplitude Mod Synth (Ideal)

slider1:carrier_freq=440<20,2000,1>Carrier Frequency (Hz)
slider2:carrier_amp=1.0<0,1,0.01>Carrier Amplitude
slider3:mod_freq=5<0.1,20,0.1>Modulator Frequency (Hz)
slider4:mod_amp=1.0<0,1,0.01>Modulator Amplitude
slider5:mod_depth=1.0<0,1,0.01>Modulation Depth
slider6:volume=0.5<0,1,0.01>Output Volume

@init
two_pi = 2 * $pi;
carrier_phase = 0;
mod_phase = 0;

@slider
// Calculate angular frequencies from sliders
carrier_inc = two_pi * carrier_freq / srate;
mod_inc = two_pi * mod_freq / srate;

@sample
// Calculate modulator and carrier signals
modulator = mod_amp * sin(mod_phase);
carrier = carrier_amp * sin(carrier_phase);

// Balanced amplitude modulation: centered around 0
// This mimics ring modulation behavior
am_signal = (1 - mod_depth) * carrier + mod_depth * (carrier * modulator);

// Scale output
output = am_signal * volume;

// Output to stereo
spl0 = output;
spl1 = output;

// Increment and wrap phases
carrier_phase += carrier_inc;
mod_phase += mod_inc;
carrier_phase >= two_pi ? carrier_phase -= two_pi;
mod_phase >= two_pi ? mod_phase -= two_pi;
```



