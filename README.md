# 85dB Differential input single end amplifier

For this project, designing a differential input single end amplifiler with one stage. The power supply is 2V and only use one current source to complete. The schematic is telescopic Cascode OP Amplifier because the design gain must be pver 85dB. 

### Design Requirment:

1. Differential voltage gain: Avd ≥ 85 dB.
2. Output voltage swing range: OVSR = Vo(max) – Vo(min) ≥ 1.3 V.
3. Average slew rate: SR ≥ 10 V/us (Average slew rate = (SR+ + SR-)/2).
4. Common mode rejection ratio: CMRR ≥ 80 dB.
5. Unity-gain bandwidth: GBW ≥ 8 MHz.
6. Phase margin: f(GBW) ≥ 60°.
7. Power dissipation (VDD): Pdiss ≤ 0.5 mW (2V) including power dissipation from all current mirrors and the current source.

### Design Spec
|     Spec      | Requirement   | Design               |
| ------------- | ------------- | ------------------   | 
|Avd (Differential voltage gain) | ≥ 85 dB  | 86.87dB  |
|OVSR (Output voltage swing range)| ≥ 1.3 V  | 1.307 V |
|SR (Average slew rate)| ≥ 10 V/us  | 8.907 V/us       |
|CMRR (Common mode rejection ratio)| ≥ 80 dB  | 87.57dB|
|GBW (Unity-gain bandwidth)| ≥ 8 MHz  | 10.2MHz        |
|PM (Phase margin)| ≥ 60°  | 61.52°                    |
|Pdiss (Power dissipation)| ≤ 0.5 mW (2V) | 0.125mW(2V)|


