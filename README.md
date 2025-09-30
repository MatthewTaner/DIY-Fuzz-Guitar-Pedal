# DIY Guitar Fuzz Pedal (Component Substitution Project)

## Project Overview

This repository documents the successful creation of a single-transistor guitar fuzz pedal. The primary challenge of this project was to adapt a classic circuit design that called for a high-gain 2N5088 transistor by substituting it with a more readily available, lower-gain PN2222 transistor. The circuit was prototyped on a breadboard and modified to achieve a similar high-gain, saturated fuzz effect.

## Technical Skills Demonstrated

* **Circuit Analysis & Prototyping:** Interpreted a common-emitter amplifier schematic and built a functional prototype on a breadboard.
* **Component Substitution:** Identified key electrical differences between the 2N5088 and PN2222 transistors.
* **Circuit Modification & Biasing:** Adjusted resistor values (R2 and R3) to re-bias the circuit and compensate for the loss in gain, ensuring proper operation of the PN2222 transistor.
* **Signal Path Understanding:** Analyzed the flow of the guitar signal through the circuit and the effect of each component.
* **Documentation:** Created clear and concise project documentation, including schematics, a Bill of Materials, and audio/video demonstrations.

## Circuit Design

The pedal is based on a simple common-emitter NPN transistor amplifier stage. The key modification involved changing the collector and emitter resistor values to push the lower-gain PN2222 transistor into a high-gain state, producing the desired fuzz effect.

* **Original Schematic:** [Link to your original schematic image]
* **Modified Schematic:** [Link to your modified schematic image, showing the new R2 and R3 values]

## Bill of Materials (BOM)

A complete list of all the components used in this project.

* **Transistor (Q1):** PN2222 NPN BJT
* **Resistors:**
    * R1: 3MΩ
    * R2: [Your new value, e.g., 50KΩ]
    * R3: [Your new value, e.g., 220Ω]
    * R4: 100KΩ
* **Capacitors:**
    * C1: 100nF
    * C2: 10nF
    * C3: 100nF
* **Potentiometer:** [Your Volume Pot value, e.g., 100KΩ log taper]
* **Power:** 9V DC supply ([Note: Must be center-negative])

## Project Demonstration

Audio and video recordings demonstrating the circuit in action, comparing the clean signal to the effected signal.

* **Audio Demo:** [Link to your audio file]
* **Video Demo:** [Link to your video file]

## Lessons Learned

* [Discuss the specific challenges you faced, such as biasing issues or unwanted noise, and how you solved them.]
* [Reflect on the difference in sound created by the component substitution and resistor changes.]
* [Any other insights or lessons from the build process.]
