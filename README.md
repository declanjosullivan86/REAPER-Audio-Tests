# Home Audio Environment Testing & Analysis

This repository contains REAPER projects and scripts designed to help analyze and improve the ambient sound, noise, vibration, and even magnetism issues within a home environment. The goal is to identify sources of unwanted interference and explore potential solutions using a systematic audio-based testing approach.

## Table of Contents

  * [Introduction](https://www.google.com/search?q=%23introduction)
  * [Features](https://www.google.com/search?q=%23features)
  * [Getting Started](https://www.google.com/search?q=%23getting-started)
      * [Prerequisites](https://www.google.com/search?q=%23prerequisites)
      * [Installation](https://www.google.com/search?q=%23installation)
  * [Usage](https://www.google.com/search?q=%23usage)
      * [Test Categories](https://www.google.com/search?q=%23test-categories)
      * [Running Tests](https://www.google.com/search?q=%23running-tests)
      * [Analyzing Results](https://www.google.com/search?q=%23analyzing-results)
  * [Contributing](https://www.google.com/search?q=%23contributing)
  * [License](https://www.google.com/search?q=%23license)

## Introduction

Modern homes are filled with a myriad of potential sources of subtle, yet impactful, audio and electromagnetic interference. From the hum of refrigerators to the buzz of power lines, these often go unnoticed but can contribute to an overall feeling of discomfort or impact sensitive audio equipment. This project leverages the powerful capabilities of REAPER DAW to create a framework for:

  * **Systematic Recording:** Capture precise audio and (indirectly) vibration/magnetism data.
  * **Targeted Analysis:** Isolate and identify specific frequencies and characteristics of unwanted sounds.
  * **Solution Exploration:** Test the effectiveness of mitigation strategies.

## Features

  * **Pre-configured REAPER Projects:** Ready-to-use project templates for various test scenarios.
  * **Custom REAPER Scripts (Planned/Future):** Automate recording, analysis, and data logging.
  * **Detailed Testing Methodologies:** Guidance on how to conduct effective tests.
  * **Example Analysis Workflows:** Demonstrations of how to interpret recorded data.
  * **Focus on Ambient Noise:** Identify and mitigate HVAC hum, appliance noise, external traffic, etc.
  * **Vibration Analysis:** Use audio recordings to infer vibration issues (e.g., resonant frequencies).
  * **Magnetism/EMI Inference:** Explore how electromagnetic interference manifests as audible noise.

## Getting Started

### Prerequisites

  * **REAPER DAW:** Download and install REAPER from [reaper.fm](https://www.reaper.fm/).
  * **Audio Interface:** A high-quality audio interface with good preamps is recommended for accurate recordings.
  * **Microphone(s):**
      * **Measurement Microphone (Recommended):** For flat frequency response and accurate ambient sound capture.
      * **Contact Microphone (for Vibration):** Essential for direct vibration measurement.
      * **Dynamic/Condenser Microphones:** Suitable for general room recordings.
  * **Optional Equipment:**
      * **EMI/EMF Meter:** For direct measurement and correlation with audio recordings.
      * **Vibration Sensor/Accelerometer:** For more precise vibration data (if not relying solely on contact mics).
      * **Headphones:** For critical listening during analysis.

### Installation

1.  **Clone this repository:**
    ```bash
    git clone https://github.com/your-username/reaper-home-audio-analysis.git
    ```
2.  **Open REAPER:**
3.  **Import REAPER Projects:** Navigate to the `reaper_projects/` directory within the cloned repository and open the desired `.rpp` files in REAPER.
4.  **Install REAPER Scripts (if any):** If there are custom scripts, follow the instructions within their respective folders (typically involving placing them in your REAPER `Scripts` directory and loading via the Actions menu).

## Usage

This project is structured around different categories of audio tests to diagnose specific issues.

### Test Categories

  * **Ambient Noise Floor Analysis:**
      * Purpose: Characterize the baseline noise level of your home in various states (e.g., all appliances off, specific appliances on).
      * Method: Long-duration recordings in different rooms.
      * REAPER Project: `ambient_noise_floor_test.rpp`
  * **Appliance Specific Noise Signature:**
      * Purpose: Identify and analyze the unique sound signatures of individual appliances (refrigerator, washing machine, HVAC, etc.).
      * Method: Record close-up to appliances, then further away.
      * REAPER Project: `appliance_signature_test.rpp`
  * **Vibration Isolation Testing:**
      * Purpose: Use contact microphones to identify sources of structural vibration and test the effectiveness of isolation solutions (e.g., rubber feet, isolation pads).
      * Method: Attach contact mic to surfaces, tap/stress points, then apply isolation.
      * REAPER Project: `vibration_isolation_test.rpp`
  * **Electromagnetic Interference (EMI) Audible Manifestation:**
      * Purpose: Investigate if and how electromagnetic fields are audibly impacting your audio environment. This often involves listening for hums or buzzes that change with the proximity of electronics.
      * Method: Record with sensitive microphones near power outlets, large electronics, and use an EMI meter for correlation.
      * REAPER Project: `emi_audible_test.rpp` (Note: This is inferential, not direct magnetic measurement via audio).

### Running Tests

1.  **Select a Test:** Open the appropriate REAPER project (`.rpp` file) for the test you wish to conduct.
2.  **Configure Input:** Ensure your audio interface inputs are correctly configured for the microphones you are using.
3.  **Position Microphones:** Follow the specific instructions within each REAPER project's notes or the `documentation/` folder for optimal microphone placement.
4.  **Record:** Arm the tracks and begin recording. Pay attention to the specific instructions for recording durations and environmental states (e.g., "all lights off," "HVAC on").
5.  **Save Recordings:** Save your recorded REAPER project with a descriptive name (e.g., `living_room_ambient_2023-10-27.rpp`).

### Analyzing Results

After recording, REAPER provides powerful tools for analysis:

1.  **Visual Inspection (Waveforms & Spectrograms):**
      * Look for consistent patterns, spikes, or specific frequencies in the waveform and spectrogram views.
      * Use REAPER's built-in `ReaEQ` or `ReaJS: gfx_spectrum_analyzer` for real-time frequency analysis.
2.  **Frequency Analysis:**
      * Use third-party VST/JSFX spectrum analyzers (e.g., SPAN, Voxengo SPAN) for more detailed frequency breakdowns.
      * Identify dominant frequencies of hums, buzzes, or resonances.
3.  **Critical Listening:**
      * Listen back to recordings carefully, especially with good headphones. Try to pinpoint the nature and location of the unwanted sounds.
      * Use EQ and filtering in REAPER to isolate specific frequencies and better understand their characteristics.
4.  **A/B Testing Solutions:**
      * After implementing a potential solution (e.g., adding isolation pads to a washing machine), re-run the relevant test.
      * Compare the "before" and "after" recordings and analyses to objectively assess the improvement.

## Contributing

Contributions are welcome\! If you have ideas for new test methodologies, REAPER scripts, or improvements to existing ones, please open an issue or submit a pull request.

Here are some areas for contribution:

  * **New REAPER Project Templates:** For different scenarios or types of interference.
  * **Custom REAPER Scripts:** To automate recording, analysis, or data export.
  * **Documentation Improvements:** Clearer instructions, more detailed analysis tips.
  * **Example Recordings/Analysis:** Share anonymized examples of problematic recordings and how they were resolved.

## License

This project is licensed under the MIT License - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.
