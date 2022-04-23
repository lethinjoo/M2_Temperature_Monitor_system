# Temperture Monitor System

## Introduction
Now a days everyone is looking for automation and advancements in all the sectors. The Vehicle Seat Heat Monitoring System is capable of maintaining of heat in the vehicles seats.
In my project, the sensor will sense is the driver has been seated or not and if the driver seated then he need to set the temperature accordingly. Based on that our controller will set the heater to required temperature. The Heater will generate the heat and a LCD display will show requested the temperature.

## Components
-   ATmega328 microcontroller along with temperature sensor,
-   Push button,
-   Heat generator,
-   LED and LCD diplay,etc.

## Atmega328
The ATmega328 is a single-chip microcontroller created by Atmel in the megaAVR family (later Microchip Technology acquired Atmel in 2016). It has a modified Harvard architecture 8-bit RISC processor core

ATmega328 is commonly used in many projects and autonomous systems where a simple, low-powered, low-cost micro-controller is needed. Perhaps the most common implementation of this chip is on the popular Arduino development platform, namely the Arduino Uno, Arduino Pro Mini[4] and Arduino Nano models.

## Push Button
A push button switch controls an action in a machine or other type of process. They are common features within the home and workplace, and are also referred to as pushbutton switches or push switches.

## Display
This LED & LCD display shows the output digitally

## Features
-   The System will sense is driver or passenger seated or not.
-   Driver or Passenger has the access to modify the temperature in the vehicle.
-   As per Drivers request, Heater will generate the heat accordingly.
-   It is best for European Countries.
-   Low cost and robust system.
-   Modular Approach.

## Behavioral Diagram

![Behavioral Diagram](https://user-images.githubusercontent.com/102732132/164073054-80343050-209c-45ad-a906-1ac1463777c9.png)

## Strutural Diagram

![Strutural Diagram](https://user-images.githubusercontent.com/102732132/164073167-42b2cbcd-fb3a-4e99-823d-4bad00535dcb.png)

## SWOT- Strengths, and Weakness, Opportunities Threats
### Strengths
-   User Friendly
-   Easy to alter the temperature inside the vehicles.
-   Modular Approach
-   Low cost and Robust system.

### Weakness
-   Its only applicable for those countries which are having low temperature.
### Opportunities
-   It can be implemented by having both Heater and AC.
### Threats
-   Not suitable for average or high temperature places.

## 4W's and 1'H
### **WHY** 
This code/simulation is user-friendly
### **WHAT** 
Temperature_Monitor_System
### **WHERE** 
Used in Automotive Industries
### **WHEN** 
At low Temperature area
### **HOW** 
System will sense the input and output

## Detail requirements
### High Level Requirements
| High Level Requirements      | Description |
| ----------- | ----------- |
| HLR1      | Microcontroller   |
| HLR2   | Temperature Sensor|
| HLR3   | Heat Generation|
| HLR4   | Display|
| HLR5   | Software used|

### Low Level Requirements
| Low Level Requirements      | Description |
| ----------- | ----------- |
| HLR1_LLR1      | ATmega328     |
| HLR2_LLR1   | LM35 and ADC|
| HLR2_LLR2   | ADC with PWM-fast|
| HLR3_LLR1   | Thermoelectric module|
| HLR4_LLR1   |LCD and LED|
| HLR5_LLR1   | Code Blocks with AVR GCC compiler |
| HLR5_LLR2   | SimulIDE |
