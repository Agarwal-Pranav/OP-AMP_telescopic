**#Overview**

This repository contains the design files and documentation for a telescopic operational amplifier (op-amp) implemented using Cadence Virtuoso. The telescopic op-amp is a high-gain amplifier architecture widely used in analog circuit design for its superior performance in terms of gain and speed.

**#Features**

Architecture: Telescopic op-amp
Designed in: Cadence Virtuoso
Applications: High-speed, high-gain analog signal amplification
Design files include: Schematic

**#Summary**

A telescopic operational amplifier (op-amp) is a type of analog amplifier architecture known for its high gain and fast speed. It uses a single-stage topology with a cascode configuration, which means that transistors are stacked to increase output resistance and gain.

**#Key Features:**

High Gain: The cascode arrangement boosts the voltage gain, making it suitable for precision analog applications.
High Speed: Fewer stages and nodes result in faster response compared to multi-stage op-amps.
Low Power: Typically has lower power consumption due to its simple architecture.
Limited Output Swing: One trade-off is that the output voltage swing is less than other architectures (such as folded cascode), since both transistors in the cascode stack must stay in saturation.

**#Applications:**

Telescopic op-amps are commonly used in high-speed analog circuits, such as data converters, sample-and-hold circuits, and as the input stage for analog-to-digital converters where high gain and speed are prioritized over maximum output swing.
