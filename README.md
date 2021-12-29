# Movable-Fire-Alarm-Robot

## Description 

We developed a sustainable surveillance robot that is const effective using an Arduino microcontroller together with some other hardware components, the robot moves inside the whole building by four wheeled dc motors help to navigate the robot and ultrasonic sensor to avoid obstacles and every one second the robot measures the temperature by a temperature sensor and also detect if there is a fire by using flame sensor and if there is a fire the robot will set off the alarm, This repo will contain the code that is deployed to the Arduino microcontroller

<img src="https://user-images.githubusercontent.com/51873396/147688054-d7f041b0-05d4-4013-a85a-2995d059b2bd.jpg" alt="drawing" width="200"/>



## Hardware specifications:

- Arduino Uno
  
<img src="https://user-images.githubusercontent.com/51873396/147688651-eac54ab9-40ed-4dca-8604-3d6346262fc1.jpg" alt="drawing" width="200"/>


Arduino Uno is a microcontroller board based on the ATmega328P It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz quartz crystal, a USB connection, a power jack, an ICSP header and a reset button. It contains everything needed to support the microcontroller

- Ultrasonic Range Finder Sensor
  
<img src="https://user-images.githubusercontent.com/51873396/147688758-8dc66142-3d9a-4296-bc97-66fa221b897f.jpg" alt="drawing" width="200"/>




Ultrasonic range finders are fun little sensors that can measure distance. You can use them to find the distance to an object, or to detect when something is near the sensor like a motion detector. They&#39;re ideal for projects involving navigation, object avoidance, and home security. Because they use sound to measure distance, they work just as well in the dark as they do in the light. The ultrasonic range finder I&#39;ll be using in this project is the HC-SR04, which can measure distances from 2 cm up to 400 cm

- H-bridge Motor Driver IC
  
<img src="https://user-images.githubusercontent.com/51873396/147688723-a83d3f9f-0044-4bf2-b5ae-fb3cca49d612.jpg" alt="drawing" width="200"/>


Generally, the H-bridge motor driver circuit is used to reverse the direction of the motor and also to break the motor. When the motor comes to a sudden stop, as the terminals of the motor are shorted. Or let the motor run free to a stop, when the motor is detached from the circuit

- Servo Motor

<img src="https://user-images.githubusercontent.com/51873396/147688752-87e679ab-5756-4022-b7f5-50c8bdf1720c.jpg" alt="drawing" width="200"/>



Servo motor used for rotating 90 degrees in each direction (180 degrees in total)

- Geared Motors x 4

<img src="https://user-images.githubusercontent.com/51873396/147688717-7c145850-cbe2-4e39-aa68-f36efcaf0632.jpg" alt="drawing" width="200"/>


A geared motor is a component whose mechanism adjusts the speed of the motor, leading them to operate at a certain speed, also geared motors have the ability to deliver high torque at low speeds

- Robot Chassis

<img src="https://user-images.githubusercontent.com/51873396/147688609-515477ee-e161-4da3-8e1a-9b4d968e9b4c.jpg" alt="drawing" width="200"/>


- Battery holder

<img src="https://user-images.githubusercontent.com/51873396/147688731-1baea7f9-b7da-4eb1-b485-ee65228a02a1.jpg" alt="drawing" width="200"/>



- Flame sensor


<img src="https://user-images.githubusercontent.com/51873396/147690807-dbeb79d0-d93b-4091-9f96-f1c976b70c0d.jpg" alt="drawing" width="200"/>



  **flame detector**  is a sensor designed to detect and respond to the presence of a flame or fire, allowing  **flame detection**. Responses to a detected flame depend on the installation, but can include sounding an alarm, deactivating a fuel line

- LM 35 temperature sensor

<img src="https://user-images.githubusercontent.com/51873396/147688743-b54a5eb2-9bb2-495e-b9d0-885089d2cae9.jpg" alt="drawing" width="200"/>

LM35 is a temperature sensor that outputs an analog signal which is proportional to the instantaneous temperature. The output voltage can easily be interpreted to obtain a temperature reading in Celsius.

- LCD

<img src="https://user-images.githubusercontent.com/51873396/147688738-f5ba9c14-d1e6-4194-8eb9-2776bad9ba50.jpg" alt="drawing" width="200"/>



A liquid crystal display or LCD draws its definition from its name itself. It is a combination of two states of matter, the solid and the liquid. LCD uses a liquid crystal to produce a visible image. Liquid crystal displays are super-thin technology display screens that are generally used in laptop computer screens, TVs, cell phones, and portable video games

## software specifications:

- ## Proteus

software tool suite used primarily for electronic design automation. The software is used mainly by electronic design engineers and technicians to create schematics and electronic prints for manufacturing printed circuit boards

- ## Arduino IDE


Arduino Software (IDE) makes it easy to write code and upload it to the board. This software can be used with any Arduino board.

- Languages: embedded C

## Circuit design
![Circut design](https://user-images.githubusercontent.com/51873396/147689742-0c735714-15e3-48a9-8036-ae02a74a1d8d.jpg)