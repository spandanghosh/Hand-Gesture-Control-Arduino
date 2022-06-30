# Hand-Gesture-Control-Arduino
1.Introduction

1.1Objective
In everyday life, humans can interact with any real-time object using their five senses: sight, hearing, smell, taste, and touch. For a long time, gesture recognition has been one of the most important aspects of sensing in the physical world.Similarly, communication between machines was a difficult task that was overcome by using specific machine understandable languages.
However, in recent years, Human Machine Interaction has emerged as one of the most difficult challenges in the field of automation.There are several approaches to the HMI challenge. Hand gestures were used to control system operations in the current work. Many existing techniques are already available in the era of hand gesture-based control systems. Some of the existing techniques for measuring hand gestures include gesture recognition using Bluetooth and motion technologies.
Nonetheless, the majority of the techniques increase the cost of the physical system. As a result, embedded systems with multiple hardware components not only improve output and response time, but also increase reliability.

There are numerous existing methods for operating system applications virtually.

Speech recognition is one of the methods used effectively to control the computer application, along with a microphone and an Arduino microcontroller. To control various computer
applications, the traditional methods of mouse, keypad, joystick, microphone, accelerometer, and touch panel can also be used.However, they are not as adaptable for use by paralysed people. However, the existing systems have some flaws, which are discussed in this section. Existing techniques have significant drawbacks, such as disabled people finding it difficult to operate Human Computer operating systems.
The main advantage of using an ultrasonic sensor is that there will be no sound noise interference in voice-controlled systems. Some external peripherals can be read and controlled without the use of any additional hardware. In this system, an ultrasonic sensor communicated directly with the computer. This methodology offers greater flexibility and simplicity of operation, that even a nonprofessional can operate the HMI system.



1.2Applications

The current systems confine users to a single location.Gadgets such as a keyboard and mouse require a supporting platform in order to be placed and interfaced with the computer.
Traditional system design is difficult due to its complexity. The complexity of advanced gesture detection systems with cameras is high in terms of cost. These issues can be solved by incorporating simple ultrasonic sensors into the existing control system.As a result, rather than using a keyboard, joystick, and mouse, an ultrasound sensor was interfaced in the current work to control computer applications.
In the current work, hand gestures sensed with ultrasonic sensor HC-SR04 are used to execute
computer applications such as volume change, scroll up/down during a website, tab change, and window change.


1.3Features
The most important aspect of this project is to write an Arduino programme that converts the distances measured by both sensors into the appropriate commands for controlling specific actions.
Here we measure the distance between your hand and the Ultrasonic Sensors in this project After
calculating the distance, the fun begins. Hand gestures performed in front of the Ultrasonic sensors can be calibrated to perform five different tasks on your computer. The five different hand gestures or actions that I've programmed for demonstration purposes are listed below.
Gesture 1: Place your hand in front of the Right Ultrasonic Sensor for a short period of time (between 15CM and 35CM) and then move your hand away from the sensor. This gesture will scroll down the page or lower the volume.
Gesture 2: For a short period of time, place your hand in front of the Right Ultrasonic Sensor at a distance (between 15CM and 35CM) and move your hand towards the sensor. This action will
either scroll up the page or increase the volume.
Gesture 3: Swipe your hand in front of the Right Ultrasonic Sensor. This action will take you to the Next Tab.
Gesture 4: Swipe your hand in front of the Left Ultrasonic Sensor. This gesture will take you to the previous tab.



Gesture 5: Swipe your hand across both sensors (Left Sensor first). This action toggles between Tasks.

The Python IDE integrates seamlessly with the Arduino UNO to achieve different processing and controlling methods for developing new gesture control solutions. Other gestures such as play or pause video and fast forward/rewind a video can also be implemented in a similar manner.


2.Design


2.1Block Diagram

We connect two ultrasonic sensors to our Arduino board at pins 10, 11 and 5, 6. 10 and 5 are connected to the Echo pin of the sensors and 11 and 6 are connected to the Trig pin of the sensors. The sensors are given a high and ground as well.


The ultrasonic sensor determines the distance of the hand by sending an ultrasonic signal. This signal then strikes our hand and is reflected back to the sensors. Trig pin is used to trigger the ultrasonic sound pulses and Echo pin produces a pulse when the reflected signal is received.










2.2Hardware Analysis

Hardware requirements include the following :

●Arduino UNO x 1

●Ultrasonic Sensors x 2

●USB Cable (for Arduino)

●Few Connecting Wires

●A Laptop with internet connection

●Breadboard 200 pins




The Arduino UNO is a microcontroller board that performs various operations in various circuits. It necessitates the use of C code, which instructs the board on what tasks to perform and how. It has 13 digital I/O pins, allowing us to control 13 different devices. The Arduino UNO has the same functionality as the Arduino Uno but in a much smaller package. The Arduino UNO board's microcontroller is an ATmega328p.
HC-SR04 board is an ultrasonic sensor which is used to determine the distance between two objects. It consists of a transmitter and a receiver. The transmitter converts the electrical signal into an ultrasonic signal and the receiver converts the ultrasonic signal back to the electrical signal.
We connect the VCC and ground pins of both ultrasonic sensors to the Arduino UNO board's 5V and ground. The first ultrasonic sensor's trig and echo pins are connected to Arduino UNO pins 11 and 10, respectively. The trig and echo pins of the second ultrasonic sensor are connected to Arduino UNO pins 6 and 5, respectively. The breadboard is used for ground connection and supplying voltage.



2.3Snapshots-Project , Team, Results
![Picture1](https://user-images.githubusercontent.com/72367806/176695506-fbbaf743-abfb-4164-a1d3-8b220581e37f.png)
![Picture2](https://user-images.githubusercontent.com/72367806/176695583-564d0edf-9572-4e3b-ae5d-638e7624639a.png)











