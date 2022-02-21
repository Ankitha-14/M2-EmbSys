# SMART BLINDSTICK USING ULTRASONIC SENSOR
# Block Diagram


![Smart Blindstick Block diagram](https://user-images.githubusercontent.com/85921878/154840562-6a8007bf-fc96-449c-8e55-f1b424aa4baf.jpeg)


* Ultrasonic sensor: Ultrasonic sensor is fixed to user's stick to detect the onstacle ,if any is present in the path. Ultrasonic sensors  collect the data and send it in real time       to the microcontroller. The  microcontroller triggers the buzzer after processing certain details.The sensor head sends out an ultrasonic signal, which is reflected by the target. Ultrasonic sensors estimate the time between outflow and gathering to determine the distance to the target.
An optical sensor has a transmitter and a receiver, whereas an ultrasonic sensor has only one ultrasonic component that is used for both discharge and gathering.
A solitary oscillator transmits and receives ultrasonic waves in an intelligent model ultrasonic sensor.
This allows the sensor head to be scaled down.

* Buzzer: It is used to sound effectively with same intensity.

* Crystal Oscillator: It is an electronic oscillator  used for the vibration contains high frequency.

* Battery: It has to be used to run the whole blindstick.A buzzer is a little but effective component that adds sound highlights to our project/framework.
Because of its small and simplified 2-pin construction, it can be used on a breadboard and  shockingly, PCBs, making it a widely used segment in most electronic applications.

* Wooden Stick: It is the main soiurce for them to walk so all are connected to the stick.

# High Level requirememnts

|ID|High kevel requirements|
|----|----------------------------| 
|HL1|Detecting the Obstacle|
|HL2|Buzzer gives sound depending on distance between user and obstacle|
|HL3|Usage of Ultrasonic sensor|
|HL4|Microcontoller that gives alert to buzzer|


# Low Level requirements
|ID|Low kevel requirements|
|----|----------------------------| 
|LL1|obstacle detects using sensor|
|LL2|Oscillator To vibrate|

# Mid Level Requirements
* To protect blind people the microcontoller and ultrasonic sensor with buzzer are connected to their stick.So sensor and controller and oscillator is also used to get vibration.
