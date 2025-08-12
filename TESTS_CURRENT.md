# Audio Test Outline: Reaper with Marantz USB Mic and JBL Speakers

## Update: 
- OFF - Pitch Shift Up & Pitch Shift Down
- OFF - AM (Low Freq) & AM (Higher Freq)

### Update - Notable Benefits
- NEW - Freq Shift +0-22khz at 25hz, normal max is 8 hz. No negative hz range.
- [2025-08-12 Freq Shift - Extreme Speed.zip](https://drive.google.com/file/d/15Z82c8qqydPJx1FhU3UnI1qgfa1SkNyP/view?usp=sharing)
- NEW - Tremelo - Invert Tremelo Phase On - Two tracks w/ Mic Input - 
- Track 1 - Low Hz of 0.1 and Track 2 - High of 20hz
- Instead of Mic Input - Used Spotify and Blackhole 2ch
  
This document outlines a multi-track audio test within the Reaper Digital Audio Workstation (DAW) environment.  
The goal is to explore various audio effects and their playback through a simple, consumer-grade speaker setup.

---

## Hardware and Software

- **DAW:** Reaper  
- **Microphone:** Marantz USB Microphone  
- **Speakers:**
  - JBL Flip 5 (Bluetooth)
  - JBL Clip 4 (Bluetooth)

---

## Test Setup

The test consists of **five tracks**, each processing the same microphone input with a unique set of effects.

# Audio Test Outline: Reaper with Marantz USB Mic and JBL Speakers

| Track | Effect | Key Settings | Mix (Wet/Dry) | Description |
|-------|--------|--------------|---------------|-------------|
| **1** | Pitch Shift Up | Pitch: +24 semitones | 50% / 50% | Harmonized octave-up mixed with original. |
| **2** | Pitch Shift Down (Wet Only) | Pitch: -24 semitones | 100% / 0% | Clean octave-down replacing original sound. |
| **3** | Tremolo | Rate: 4 Hz, Depth: 50%, Phase: Inverted, Waveform: Sine | N/A | Pulsating effect, starts at minimum amplitude. |
| **4** | AM (Low Freq) | Carrier: 0.1 Hz, Mod: 0.01 Hz, Depth: 2–3, Amp: 1.0 | N/A | Slow cyclical volume sweeps with subtle variation. |
| **5** | AM (Higher Freq) | Carrier: 1 Hz, Mod: 0.1 Hz, Depth: 2–3, Amp: 1.0 | N/A | Noticeable wobble with slower underlying variation. |

---

## Hardware & Software
- **DAW:** Reaper  
- **Mic:** Marantz USB Microphone  
- **Speakers:**
  - JBL Flip 5 (Bluetooth)
  - JBL Clip 4 (Bluetooth)

---

## Playback Configuration
- **Speaker Placement:** JBL Flip 5 and Clip 4 placed in different locations for spatial perception.  
- **Evaluation Goal:** Test clarity/audibility of effects (esp. Tremolo & AM) on consumer-grade Bluetooth speakers with limited bass response.

### Track 1: Pitch Shift Up
- **Input:** Marantz USB Microphone  
- **FX:** Pitch Shifter (e.g., Reaper's built-in ReaPitch)  
  - Pitch Shift: `+24 semitones`
  - Mix:
    - Wet: `50%`
    - Dry: `50%`
- **Description:**  
  Creates a harmonized, octave-up version of the input, mixed with the original signal.

---

### Track 2: Pitch Shift Down (Wet Only)
- **Input:** Marantz USB Microphone  
- **FX:** Pitch Shifter (e.g., Reaper's built-in ReaPitch)  
  - Pitch Shift: `-24 semitones`
  - Mix:
    - Wet: `100%`
    - Dry: `0%`
- **Description:**  
  Produces a clean, octave-down version of the input signal, completely replacing the original sound.

---

### Track 3: Tremolo
- **Input:** Marantz USB Microphone  
- **FX:** Tremolo (e.g., Reaper's built-in Tremolo or a similar plugin)  
  - Rate/Frequency: `4 Hz`
  - Depth: `50%`
  - Phase: Inverted
  - Waveform: Default (e.g., sine wave)
- **Description:**  
  The audio has its volume modulated 4 times per second, creating a pulsating effect.  
  The inverted phase starts modulation at a minimum amplitude instead of maximum.

---

### Track 4: Amplitude Modulation (Low Frequency)
- **Input:** Marantz USB Microphone  
- **FX:** Amplitude Modulation (AM) plugin  
  - Carrier Frequency: `0.1 Hz`
  - Modulation Frequency: `0.01 Hz`
  - Carrier Amplitude: `1.0`
  - Modulation Amplitude: `1.0`
  - Modulation Depth: `2` or `3`
- **Description:**  
  Produces a slow, dramatic amplitude modulation.  
  The extremely low carrier frequency causes long, cyclical volume sweeps.  
  The even lower modulation frequency adds subtle secondary volume variation.

---

### Track 5: Amplitude Modulation (Higher Frequency)
- **Input:** Marantz USB Microphone  
- **FX:** Amplitude Modulation (AM) plugin  
  - Carrier Frequency: `1 Hz`
  - Modulation Frequency: `0.1 Hz`
  - Carrier Amplitude: `1.0`
  - Modulation Amplitude: `1.0`
  - Modulation Depth: `2` or `3`
- **Description:**  
  Applies a more audible amplitude modulation.  
  The `1 Hz` carrier creates a noticeable wobble, while the `0.1 Hz` modulation adds a slow variation to it.

---

## Playback Configuration

The test will be performed by **playing all five tracks simultaneously** through the two JBL Bluetooth speakers.

- **Speaker Placement:**  
  Place the JBL Flip 5 and Clip 4 in different locations to evaluate spatial characteristics and how each effect is perceived from different points in the room.

- **Evaluation:**  
  Assess the clarity and audibility of effects — especially low-frequency ones like Tremolo and AM — on consumer-grade speakers with limited bass response.  
  The goal is to determine how subtle sound manipulations translate to a real-world listening environment.
