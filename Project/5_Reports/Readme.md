# Introduction
   As the non renewable energy resources are decreasing, use of renewable resources for producing electricity is increasing. Solar panels are becoming more popular day by day. Solar panel absorbs the energy from the Sun, converts it into electrical energy and stores the energy in a battery.This energy can be utilized when required or can be used as a direct alternative to the grid supply. Utilization of the energy stored in batteries is mentioned in below given applications. The position of the Sun with respect to the solar panel is not fixed due to the rotation of the Earth. For an efficient usage of the solar energy, the Solar panels should absorb energy to a maximum extent. This can be done only if the panels are continuously placed towards the direction of the Sun. So, solar panel should continuously rotate in the direction of Sun. This describes about circuit that rotates solar panel.

# Block Diagram
![blockdiagram](https://user-images.githubusercontent.com/42490038/157283068-727c7d3c-1952-43cc-addf-74b7c4242b28.png)

# Flowchart
![flowchart](https://user-images.githubusercontent.com/42490038/157287806-8b8a51a9-c353-40d3-b498-65602f78eb0f.png)

# Components required
- Solar panel
  - A solar panel is a collection of solar (or photovoltaic) cells, which can be used to generate electricity through photovoltaic effect.
- Arduino Uno
  - Arduino Uno is a microcontroller board based on the ATmega328P. It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz quartz crystal, a USB connection, a power jack, an ICSP header and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with a AC-to-DC adapter or battery to get started.
- Light Dependent Resistor
  -  LDRs light sensitive devices most often used to indicate the presence or absence of light, or to measure the light intensity.
- Servo Motor
  - Servo motor is used to rotate the panel.
- Resistor
- Capacitor

# **4Ws 1H**
- Who
  - This is very useful for farmers.
- When 
  - When there is a ample amount of sunlight.
- Where
  - All the Places where Sunlight is mostly available.
- Why
  - To generate high amount of power.
- How
  - Based on the light falling on the two LDRs, the Microcontroller changes the position of the Servo Motor which in turn moves in the panel.


# **SWOT Analysis**
- Strength:
  - More light will be absorbed by solar panel and more amount of power is generated. 
- Opportunities:
  - Growing innovations in solar technology.
- Weakness:
  - Large dependency on sunny weather.
- Threats:
  - Cumbersome maintenance and repair.

# **HIGH LEVEL TEST PLAN**
| Test ID | Description | Expected Input | Expected Output | Actual Output |
| ------- | ----------- | -------------- | --------------- | ------------- |
| H1 | Movement of solar panel through servomotor | Servomotor should rotate with respect to which LDR detects high intensity of light | Servomotor should rotate | Servomotor rotates |
| H2 | High, Low, Medium solar light | Sunlight | Servomotor should rotate with respect to which LDR detects high intensity of light | Servomotor rotates according to intensity of light |

# **LOW LEVEL TEST PLAN**
| Test ID | Description | Expected Input | Expected Output | Actual Output |
| ------- | ----------- | -------------- | --------------- | ------------- |
| L1 | Detection of Solar light | Sunlight | Servomotor should rotate | Servomotor rotates |
