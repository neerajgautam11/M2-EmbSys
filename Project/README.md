# Seat Heating System
Embedded C Mini Project

Codacy 
-------------------------------------------------------------
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/9f3c279bcb0f422481ba34c59d02c0ad)](https://www.codacy.com/gh/neerajgautam11/M2-EmbSys/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=neerajgautam11/M2-EmbSys&amp;utm_campaign=Badge_Grade)

Codiga
-------------------------------------------------------------
![Codiga Badge](https://api.codiga.io/project/31465/score/svg)
![Codiga Badge](https://api.codiga.io/project/31465/status/svg)

CI
---------
[![CI](https://github.com/neerajgautam11/M2-EmbSys/actions/workflows/main.yml/badge.svg)](https://github.com/neerajgautam11/M2-EmbSys/actions/workflows/main.yml)
# **Introduction:**

The heating system is basically used to control the temperature. The user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the activities of the control system are done on a microcontroller called Atmega328. The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE.

## Abstract

A heating system is a mechanism for maintaining temperatures at an acceptable level ,by using thermal energy within Everywhere like home , cars etc. It helps the system to raise the temperature of an enclosed space for the primary purpose of ensuring the comfort of the occupants.The Seat Heating control system is mostly  used to control the temperature of a car seat. When a passenger or a driver of the car sits on the car seat, the button sensor gets activated (which acts as one switch). After that, the user has to turn on the heater(It's called the recirculation button, and it plays an important role in the heat).The temperature sensors work by measuring the temperature that's being given off by the thermostat and/or the coolant itself, and it also  keeps monitoring and recording the temperature and sends the analog value to the microcontroller ATmega328. The microcontroller takes the analog input of the temperature sensor and gives output a temperature value through  USART(universal synchronous and asynchronous receiver and transmitter).

# **Research:**

Seat warmers were first introduced by Cadillac in 1966 to help with backaches. Some vehicles come with car seat warmers, which heat up the seat with the push of a button. Normally the buttons are located on the side of the driver and passenger door. In some vehicles, just the bottom of the seat warms up, where in others both the bottom and back warm up.

# **Benefits:**

Heated seats can make cars much more comfortable in the winter, or for those who often get cold even in the summer. The heater in most vehicles work well, but the car’s seat warmer is close to your body allowing you to warm up faster. In some cases, the seat warms up before the rest of the vehicle does.

## Components used
- ATMEGA 328
- Temperature Sensors
- LCD ( liquid crystal display)
- LED (Light-emitting diode) 
- Heater core
- Thermostat

## Software used

- SimulIDE

- GCC Compiler for AVR

- VS Code


## Details requirements
### High Level Requirements:
| ID | Description | Status |
|------| ------| ------|
| HLR1 | When the two switches are closed, the first LED glows indicating the actuation of the system and the heater. | Implemented
|HLR2  | Next the analog input from the temperature sensor is received and digitized.| Implemented
|HLR3  | The hard disk must be 4 GB . |	Implemented
|HLR4  | The web browser must be Microsoft Internet Explorer with a resolution of at least 800 \* 600. |	Implemented

#### Low Level Requirements:

| ID | Description | Status |
|-------|------|------|
| LLR1 | The digitized temperature input is visualized using Pulse Width Modulation.| Implemented 
| LLR2 | The system runs effectively on Windows 2000 server but it will also run equally well on compatible operating systems.  | Implemented
| LLR3 | The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.| Implemented 
 
# **SWOT Analysis:**

**Strength:**

The advantage of such devices is that you can not wait until the entire salon warms up, and immediately go on business. After all, heating has a local effect, so they do their job in 2-5 minutes.

**Weakness:**
- If you do not follow the recommendations and go too far with the temperature, this can lead to a decrease in the driver’s attentiveness, cause fatigue and headaches, and also increase the risk of catching a cold due to a violation of the body’s temperature regime.
- the power cord is plugged in only after you fix the cape;
- if you spill any liquid on the heater cover, immediately turn off the device;
- if you leave the car, do not leave the device turned on;
- you can not wash the capes, iron, maximum-shake;
- Use dry bags to store the heater.

**Opportunities:**

The advanced technologies in automotive seat heaters are predicted to increase the growth of the market in the review period. The latest features like modern seat heaters like consistent and controlled warmth, heating level adjustment are attracting the consumers and are expected to propel the market growth. Growing demand for comfort and energy capabilities in vehicles is accelerating market growth.

**Threats:**
- A lack of regulation for these seats has left consumers more open to injuries.
- Within 10 minutes at 120 degrees an individual can experience third-degree burns. For those with the inability to feel the temperature at the time, this can prove even more dangerous. Those who have been diagnosed with conditions such as paralysis, diabetes, and neuropathy are less like to feel the heat in their lower extremities.
- High electrical resistance could cause the heater pad in the seat to overheat.

# **4W and 1H:**

**What:**
Heated seats can make cars much more comfortable in the winter, or for those who often get cold even in the summer. The heater in most vehicles work well, but the car's seat warmer is close to your body allowing you to warm up faster. In some cases, the seat warms up before the rest of the vehicle does.

**When:**
Heated front seats not only offer luxurious comfort, relaxation and benefits for physical health, but also increase safety. Heating seats and backrests ensures a high level of well-being and prevents a cramped posture. Winter clothes limiting freedom of movement can be dispensed with. This also results in better operation of the restraint system by reducing the slack in safety belts. People with back or kidney problems benefit from a possible reduction of pain. It is mostly used in cars.

**Where:**
In car seats

**Why:**
Heated seats can bring a lot of different benefits beyond just having a nice and warm place to sit. The single greatest benefit that heated seats can bring is the therapeutic warmth it offers. This is great for older drivers or people with a few aches and pains.

**How:**
The longer the seat cushion stays on, the hotter it gets. If it were to stay on for too long, it would get hot enough to become uncomfortable or even dangerous to sit in. It could even start a fire in the cushion. To prevent this, most car seat heaters have a thermostat. The thermostat measures the temperature in the cushion. When it reaches a certain temperature, the thermostat sends a signal, automatically turning off the relay until the seat cools down a bit. At that point, the thermostat turns the relay back on again. Many seat cushions also have “high” and “low” settings that let the driver control the temperature of the seat cushions.

# DESIGN:-

# **Behavioral Diagram:**
![image](https://user-images.githubusercontent.com/80674639/116705858-a1631a00-a9ea-11eb-847d-96b0c179f015.png)

# **Structural Diagram:**

## High Level Diagram
![Structural](https://user-images.githubusercontent.com/94169797/143780041-8d337aab-0320-4b27-8c46-32ce86d2cd95.jpeg)
## Low Level Diagram
![Structural Diagram png](https://user-images.githubusercontent.com/98817564/155724258-2d726c05-09fd-43ea-8878-25d478d96fbb.png)

### Heating Core
Heater Core used in heating the cabin of a vehicle.

### Heating Control Engine
The warmth from the engine goes from the radiator to the heater core, which basically acts as a heat exchanger.

### Water Pump
A working water pump is vital for the engine; if the water pump doesn't work, the engine will overheat.

### Hot Coolant
The hot coolant passes down through the radiator, it cools down.

### Thermistor
When the engine reaches normal operating temperature, the thermostat opens, allowing the flow of hot coolant through the radiator. 
The thermistor controls the temperature of the boiler water. On one terminal, it connects to the temperature setting or the potentiometer.

### Radiators
Radiators work through a heat transfer process called convection. When water in the radiator is heated, the surrounding air is also heated up via convection and this hot air is then moved around the room as the air circulates.

### Blower Motor
The blower motor turns the blower fan, sending the air through your air ducts and into the car . 

### Hot Water Valve
It Desires water temperature and then the valve mixes hot water from your tank with regular cold water until it gives you the temperature you want.
 
### Cabin Air Filter
An air cabin filter is an important component in any vehicle's heating System. It helps protect the passengers from contaminants in the air they breathe.
 
### Fresh Air
Adding fresh air to a heating system accomplishes two primary indoor air quality goals. It pressurizes a building and increases indoor air quality by diluting  polluted or stale indoor air.
 
### Coolant Expansion Tank
It allows the coolant, the antifreeze, and the air in the system to expand with rising temperature and pressure.


# **Block Diagram:**
![144034851-3053d0b6-31b8-46e8-9880-0be2429864c9](https://user-images.githubusercontent.com/98866993/155888502-6ffb82e8-35fe-4791-b771-e48afd47a3d4.png)
## Atmega 328
It enables to measure the heat output as well as control a circulation pump.
## Sensors
If your vehicle has automatic climate control, it uses sensors to monitor the cabin, and then opens or closes the blend doors and outside flap as needed to maintain the         temperature have Been set.
## Power Supply
The purpose of a mains power supply is to convert the power delivered to its input by the sinusoidally alternating mains electricity supply into power available at its output in the form of a smooth and constant direct voltage.
## Heater Core
Heater Core basically acts as a heat exchanger. It allows coolant to flow through, and this flow of coolant is regulated by the heater control valve. As the engine's heat is carried by coolant into the heater core, the device starts to get warm.
## LED
When this Led flicks , it means that the coolant level is running low. It may also mean the possibility of the engine overheating and you need to stop your vehicle immediately.

 
# **Flow Chart:**
![Flowchart](https://user-images.githubusercontent.com/98866993/155888443-5b3a7906-2270-4973-a531-ea66883acd1f.png)







