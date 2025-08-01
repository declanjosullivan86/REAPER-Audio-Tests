# Tests Performed

This document provides a detailed log of the audio tests conducted using REAPER, outlining the specific configurations and equipment used for each.

| Test ID | Date | Test Category | Specific Test | REAPER Project File | Microphone(s) Used | Speaker(s) Used (if applicable) | Audio Interface | Notes/Observations |
| :------ | :--- | :------------ | :------------ | :------------------ | :----------------- | :------------------------------ | :-------------- | :----------------- |
| **AMB-001** | 2025-07-28 | Ambient Noise Floor | Living Room Baseline (Empty) | `ambient_noise_floor_test.rpp` | Rode NT1-A (Mono) | N/A | Focusrite Scarlett 2i2 | All appliances off, windows closed. Recorded for 30 min. |
| **AMB-002** | 2025-07-28 | Ambient Noise Floor | Living Room Baseline (with Fridge) | `ambient_noise_floor_test.rpp` | Rode NT1-A (Mono) | N/A | Focusrite Scarlett 2i2 | Only refrigerator on. Recorded for 15 min. Hum at 60Hz visible. |
| **APL-001** | 2025-07-29 | Appliance Specific Noise | Refrigerator Hum (Close-up) | `appliance_signature_test.rpp` | Shure SM57 (Mono) | N/A | Focusrite Scarlett 2i2 | Mic ~10cm from compressor. Clear motor hum and vibration noise. |
| **APL-002** | 2025-07-29 | Appliance Specific Noise | Washing Machine Spin Cycle | `appliance_signature_test.rpp` | Rode NT1-A (Mono) | N/A | Focusrite Scarlett 2i2 | Mic ~1m from washing machine during spin. High-frequency whine. |
| **VIB-001** | 2025-07-30 | Vibration Isolation | Washing Machine (No Isolation) | `vibration_isolation_test.rpp` | Piezo Contact Mic (Mono) | N/A | Focusrite Scarlett 2i2 | Contact mic on top panel. Significant resonance detected. |
| **VIB-002** | 2025-07-30 | Vibration Isolation | Washing Machine (with Rubber Feet) | `vibration_isolation_test.rpp` | Piezo Contact Mic (Mono) | N/A | Focusrite Scarlett 2i2 | Same test as VIB-001, after installing rubber feet. Reduced resonance. |
| **EMI-001** | 2025-07-31 | EMI Audible Manifestation | PC Tower Proximity Hum | `emi_audible_test.rpp` | Rode NT1-A (Mono) | N/A | Focusrite Scarlett 2i2 | Mic ~30cm from PC tower. Audible electrical hum. |
| **SPK-001** | 2025-08-01 | Speaker Characterisation | Monitor Speaker (Left) - Flat | `speaker_test.rpp` | MiniDSP UMIK-1 (Mono) | KRK Rokit 5 G4 (Left) | Focusrite Scarlett 2i2 | Pink noise played through left speaker. Measured with calibrated mic. |
| **SPK-002** | 2025-08-01 | Speaker Characterisation | Monitor Speakers (Stereo) - Flat | `speaker_test.rpp` | MiniDSP UMIK-1 (Stereo Pair) | KRK Rokit 5 G4 (Pair) | Focusrite Scarlett 2i2 | Pink noise played through both speakers. Stereo recording of room response. |
| **MIC-001** | 2025-08-01 | Microphone Comparison | Ambient Room - Rode NT1-A | `mic_compare_test.rpp` | Rode NT1-A (Mono) | N/A | Focusrite Scarlett 2i2 | Recorded silence in the room for 5 min. For noise floor comparison. |
| **MIC-002** | 2025-08-01 | Microphone Comparison | Ambient Room - Shure SM57 | `mic_compare_test.rpp` | Shure SM57 (Mono) | N/A | Focusrite Scarlett 2i2 | Recorded silence in the room for 5 min. For noise floor comparison. |
| **MIC-003** | 2025-08-01 | Microphone Comparison | Ambient Room - Stereo Pair | `mic_compare_test.rpp` | Behringer C-2 (Stereo Pair) | N/A | Focusrite Scarlett 2i2 | Recorded silence in the room for 5 min. For stereo imaging. |
