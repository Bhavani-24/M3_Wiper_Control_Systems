# Aim
Wiper control system designed uses STM32F407VG as the main controller, which senses the severity of rain or snow and helps in varying the speeds of wiper according without any manual intervention. Usually, the wiper is attached to the front and rear sides. With the wiper, the driver’s view will not be hindered and so they can see clearly towards the front or rear. Wipers do have a very important role in the safety of the riders because wiper performance is closely related to the safety of driving.

# Objectives
- The main objective is to design and manufacture a new mechanism to cover the complete area of the wind screen.
- The main purpose of the wiper system is to clean the windscreen sufficiently to provide suitable visibility at all times.
- At present, engineers are investigating fully automated systems that vary the speed of the wiper blades according to the rate of the rainfall and the speed of the vehicle.
- The systemcontains a microcontroller that takes in the input signals from the sensors and controls the operation of the windshield wipers based on those input signals.

# Introduction
wipers are manual systems that work on the principle of manual switching. So here we propose an automatic wiper system that automatically switches ON on detecting rain and stops when rain stops. Our project brings forward this system to automate the wiper system having no need for manual intervention. For this purpose we use rain sensor along with microcontroller to drive the wiper motor. 

## Wiper working
Our system uses rain sensor to detect rain, this signal is then processed by microcontroller to take the desired action. The rain sensor works on the principle of using water for completing its circuit, so when rain falls on it it’s circuit gets completed and sends out a signal to the microcontroller. The microcontroller now processes this data and controls the motor.This system is equally useful for Aircrafts and a smaller version of this can be used by motor bikers in their helmets so that they can drive easily in rains. When the wiper switch is in the off position, the wiper will not function. When the wiper switch is in low-speed mode, the wiper will work at low speed. Accordingly, when the wiper switch is in high-speed mode, the wiper will work at a fairly high speed.
Now that you hopefully understand how the car wiper works, along with its components and detail functions, you should take care of it as well as possible and be diligent in cleaning it!

# Features
- It can control wiper action wirhout human intervention.
- It is reliable and easy to configure.
- It offers three different modes of control - low speed, medium speed, high speed.

# 4W's and 1H

- What : Automatic wiper control system using the microcontroller STM32407VG
- When : when the visibility of the road is compromised due to rain, snow, dust.
- Where : On the windshield of the vehicle.
- Why : To improve the visibility of the road, to prevent accidents and to ensure safe travel.
- How :By designing an embedded system controller to control the wiper arm action according to severity of conditions without human intervention.

# SWOT Analysis
## strengths                                                            
- electronic and speed control reduced noise at blade reversal points.   
- Reduced weight of the motor and size of the motor.                    
- Enhanced driver comfort reduced noise from wiper operation.            

## weakness
- Additional cost is required to install this system for four wheelers.
- It is not applicable for two wheelers.
- This system applied in the case of water falling on the glass only.

## Opportunities
- The wiper system of a vehicle is an integrated system that is used to remove rain, dust, oil from a windscreen or windshield.
- It greatly makes the visibility and affets the safety of passengers and the vehicles also.

## Treats
A Wiper Attack involves wiping/overwriting/removing data from the victim.

# Requirements

## High Level Requirements
 LLR_ID | Description | Status
------ | ----------- | -------
HLR_1 | The red LED is on to indicate the Ignition key position at ACC | Implemented
HLR_2 | LEDs come in desired pattern at set frequency replicating speed control of wiper arm| Implemented
HLR_3 | The Red LED is off to indicate the ignition | Implemented


# Low Level Requirements 
LLR_ID | Description | Status
----- | ------------ | -------
LLR_1 |  LEDs come on in desired pattern at set frequency at 1Hz(Low speed) | Implemented
LLR_2 | LEDs come on in desired pattern at set frequency at 4Hz(medium speed)  | Implemented
LLR_3 | LEDs come on in desired pattern at set frequency at 8Hz(high speed) | Implemented

# References
* https://www.st.com/resource/en/datasheet/stm32407vg.pdf
* https://www.st.com/resource/en/reference_manual/rm0090-stm32f405415-stm32f407417-stm32f427437-and-stm32f429439-advanced-armbased-32bit-mcus-stmicroelectronics.pdf
* https://www.st.com/resource/en/data_brief/stm32f4discovery.pdf
