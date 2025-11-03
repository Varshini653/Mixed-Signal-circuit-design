# Mixed-Signal-circuit-design  
# A Transconductance-Enhanced Latch Comparator for Energy-Efficient High-Speed ADCs
# Abstract
This work introduces a low-power, high-speed dynamic comparator designed for analog-to-digital converter (ADC) applications. The key innovation lies in a transconductance-enhanced latching stage that, unlike conventional cross-coupled inverters, biases all transistors in strong inversion during the reset phase. This approach significantly improves effective transconductance at the beginning of the comparison, resulting in faster regeneration, reduced metastability, and lower energy consumption. Implemented in 180-nm CMOS technology and operating at a 1.2 V supply, the comparator achieves a sampling speed of up to 2 GS/s while consuming only 110 fJ per comparison. Both simulation and measurement results validate its reduced delay, compact area, and superior energy efficiency, making it highly suitable for high-performance, low-voltage ADCs.
# Keywords
Dynamic Comparator, Transconductance Enhancement, Latch Regeneration, Low Power, High Speed, Analog-to-Digital Converter (ADC).
# Introduction
Dynamic comparators are vital in ADCs, high-speed I/O, memory sensing, and BIST circuits due to their fast operation and low static power. Conventional single-stage designs suffer from high voltage headroom requirements and kickback noise. Two-stage topologies with separate preamplifiers offer better low-voltage performance and noise isolation. Prior enhancements have improved speed and power but often increased area or noise. This paper presents a novel two-stage dynamic comparator with a transconductance-enhanced latching stage, achieving faster regeneration and lower energy consumption. Fabricated in 180-nm CMOS, it operates at 1.2 V with 2 GS/s sampling and 110 fJ energy per comparison.

# Circuit Implementation
<img width="1209" height="803" alt="ss_crop" src="https://github.com/user-attachments/assets/969e0633-4397-424a-8df3-1e07f1ca0920" />



