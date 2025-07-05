# Fundamental Electrical Circuits and Instrumental Measurements

This repository documents the first laboratory session for BEGY 6503: Biomedical Instrumentation. The objective of this lab was to explore fundamental electrical circuits and perform key measurements using instruments such as oscilloscopes, function generators, and digital multimeters.

Conducted by Group 1:  
Ameya Srivastava, Mariam Zoair, Reem Aboutaleb

---

## Objective

To build and analyze simple electrical circuits and gain hands-on experience in measuring voltage, current, resistance, and waveform characteristics. The lab emphasized accuracy in manual measurements and comparison against theoretical values to understand instrument calibration, limitations, and error rates.

---

## Overview of Activities

The lab was divided into two main modules:

1. **Signal Observation and Analysis using Oscilloscope**
2. **DC Circuit Analysis using Multimeters**

Each task involved both experimental execution and computational analysis, comparing practical observations with theoretical expectations.

---

## Key Experiments & Results

### Signal Generation and Oscilloscope Measurements

- **Waveform Visualization**  
  Captured sine waveforms showing 2 and 4 cycles using horizontal control.

- **Trigger Settings**  
  Observed effects of Rise and Fall slopes. Demonstrated unstable waveform display when trigger level exceeded signal range.

- **Cursor Measurements**  
  - Peak-to-Peak Voltage: 400.00 mV  
  - Period: 500.08 µs  
  - Error rates (manual vs. measured):  
    - Peak-to-Peak: 0.5%  
    - Period: 2.38%

- **Oscilloscope “Meas” Function Output**  
  Includes voltage, period, frequency, rise/fall times, RMS values.

- **DC Offset Adjustments**  
  Compared AC RMS and DC RMS values under offset conditions. Theoretical RMS closely aligned with DC RMS output.

---

### Resistance and Circuit Analysis

#### Resistance Measurement

| Resistor | Nominal Value | Measured Value | Error Rate |
|----------|----------------|----------------|------------|
| R1       | 10 kΩ          | 9.84 kΩ        | 1.6%       |
| R2       | 12 kΩ          | 11.78 kΩ       | 1.83%      |
| R3       | 15 kΩ          | 14.68 kΩ       | 2.13%      |
| R4       | 18 kΩ          | 17.56 kΩ       | 2.4%       |

#### Series Circuit Voltage Measurement

| Quantity | Measured (V) | Theoretical (V) | Error (%) |
|----------|---------------|------------------|-----------|
| VBA      | 1.0999        | 1.0900 (nominal) | 0.90      |
| VDC      | 1.6329        | 1.6350 (nominal) | 0.128     |

#### Series Circuit Current Measurement

| Quantity | Value         | Source       | Error (%) |
|----------|---------------|--------------|-----------|
| Current  | 110.852 µA    | Measured     | —         |
|          | 109.09 µA     | Theoretical  | 1.6       |

#### Parallel Circuit Voltage and Current

- **Voltage across R4**  
  - Measured: 2.9312 V  
  - Theoretical: 2.944 V (nominal)  
  - Error: 0.43%

- **Current through R3**  
  - Measured: 205.25 µA  
  - Theoretical: 203.6 µA (nominal)  
  - Error: 0.94%

---

## Measurement Error Analysis

Measurement errors were calculated by comparing practical values with both theoretical values derived from nominal and true resistance values. Most errors remained under 2%, indicating good calibration and experimental technique.

---

## Tools and Instruments Used

- Digital Oscilloscope
- Function Generator
- Digital Multimeter
- Resistors (10kΩ–18kΩ)
- Breadboard & Connecting Wires
- Power Supply Unit

---

## Conclusion

This lab session provided a practical foundation in constructing and analyzing basic electrical circuits. Students developed proficiency in using measurement tools, interpreting waveform behavior, and understanding error sources. The observed measurements closely aligned with theoretical predictions, validating both circuit design and measurement accuracy.

This experience forms the cornerstone for future labs involving more advanced biomedical instrumentation topics.

---
