# DIY Guitar Fuzz Pedal (Component Substitution Project)

## Project Overview

This repository documents the successful creation of a single-transistor guitar fuzz pedal. The primary challenge of this project was to adapt a classic circuit design that called for a high-gain 2N5088 transistor by substituting it with a more readily available, lower-gain PN2222 transistor. The circuit was prototyped on a breadboard and modified to achieve a similar high-gain, saturated fuzz effect.

## Technical Skills Demonstrated

* **Circuit Analysis & Prototyping:** Interpreted a common-emitter amplifier schematic and built a functional prototype on a breadboard.
* **Component Substitution:** Identified key electrical differences between the 2N5088 and PN2222 transistors.
* **Circuit Modification & Biasing:** Adjusted resistor values (R2 and R3) to re-bias the circuit and compensate for the loss in gain, ensuring proper operation of the PN2222 transistor.
* **Signal Path Understanding:** Analyzed the flow of the guitar signal through the circuit and the effect of each component.

## Circuit Design

The pedal is based on a simple common-emitter NPN transistor amplifier stage. The key modification involved changing the collector and emitter resistor values to push the lower-gain PN2222 transistor into a high-gain state, producing the desired fuzz effect.

* See FuzzSchematic.jpg for schematic information

## Bill of Materials (BOM)

A complete list of all the components used in this project.

* **Transistor (Q1):** PN2222 NPN BJT
* **Resistors:**
    * R1: 1MΩ
    * R2: 100kΩ
    * R3: 30kΩ
    * R4: 220Ω
* **Capacitors:**
    * C1: 100nF
    * C2: 100nF
* **Potentiometer:** 100KΩ log taper
* **Power:** 9V DC supply

## Project Demonstration

Audio and video recordings demonstrating the circuit in action, comparing the clean signal to the effected signal.

* **Audio Demo:**
* See FuzzAudioDemo.wav for audio demonstration of clean tone vs. fuzz tone.
* **Notice** Gain is increased in the second version of the bass line. The fuzz version is much fuller and saturated than the original, clean version.

## Project Challenges

* The largest setback for this project was the lack of components. I did not have many of the original schematic's parts, so I had to use the parts I had to replicate the tone of the original.
* The main component I was forced to work with was the PN2222 transistor. This also caused me to use three resistors together to create a custom resistance to increase gain.
* This extra gain made up for the loss of gain by using a PN2222 transistor.
