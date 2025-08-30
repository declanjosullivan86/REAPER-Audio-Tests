# Pitch vs Frequency Shifters

ReaPitch and MFreqShifter represent two fundamentally different approaches to altering the frequency content of a sound: pitch shifting and frequency shifting. The key difference lies in how they handle **harmonic relationships**.

***

### Pitch Shifting (ReaPitch)

Pitch shifting, as performed by plugins like **ReaPitch**, transposes the entire audio signal up or down while maintaining the **harmonic relationships** between the fundamental frequency and its overtones.  This means if you have a sound with a fundamental frequency of 100 Hz and harmonics at 200 Hz and 300 Hz, shifting the pitch up by an octave will result in a new fundamental at 200 Hz and new harmonics at 400 Hz and 600 Hz. The ratios (2:1 and 3:1) are preserved.

This method is ideal for sources that have a clear pitch and harmonic structure, such as:

* **Vocals:** You can correct an out-of-tune note or create harmonies that sound natural and in key.
* **Acoustic Instruments:** Shifting a guitar or piano part up or down a semitone to fit a new key without having to re-record.
* **Melodic Synthesizer Leads:** Transposing a synth melody to create a higher or lower part that fits within the existing chord progression.

***

### Frequency Shifting (MFreqShifter)

Frequency shifting, used by plugins like **MFreqShifter**, adds or subtracts a fixed amount of Hertz (Hz) to every frequency component in the signal. This **does not preserve harmonic relationships**. For example, if you shift the same 100 Hz sound with harmonics at 200 Hz and 300 Hz up by 50 Hz, the resulting frequencies will be 150 Hz, 250 Hz, and 350 Hz. The original ratios are now destroyed, creating an **inharmonic** or "atonal" sound.

Because it breaks the natural harmonic structure, frequency shifting is more useful for creative sound design and can produce unique, often metallic or bell-like textures. It's often used on sources where the original pitch is not the primary focus, such as:

* **Digital Sound Production Elements:** Making synthesizers, drones, or pads sound more complex and evolving.
* **Percussion and Drums:** Applying a slight frequency shift can add a metallic clang to a snare or a unique sweep to a cymbal.
* **Sci-Fi/Robotic Effects:** Shifting a vocal or sound effect by a large amount to create an unnatural, alien, or robotic texture.
* **Subtle Stereo Widening:** Applying a very small shift to one channel to create a psychoacoustic sense of width and movement.
