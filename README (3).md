## **1\. Abstract**

The Smart Automatic Safety Gate is an Arduino-based system designed to detect nearby obstacles and automatically control a gate. An ultrasonic sensor continuously measures the distance of an object. When an obstacle is detected between 20 cm and 50 cm, the buzzer produces an alert sound and the servo motor moves the gate to the closed position. The project demonstrates the integration of sensing, alert generation, and automatic mechanical control.

## **2\. Description**

This project uses an Arduino, ultrasonic sensor, buzzer, and servo motor connected through a breadboard. The ultrasonic sensor monitors the area in front of the system and measures the distance of nearby objects. When an obstacle enters the 20–50 cm range, the Arduino activates the buzzer and commands the servo motor to close the gate. This provides a simple prototype of an automated safety barrier.

## **3\. Materials Required**

* Arduino Uno  
* HC-SR04 Ultrasonic Sensor  
* Servo Motor  
* Buzzer  
* Breadboard  
* Jumper Wires  
* USB Cable  
* Computer or Laptop

## **4\. Procedure**

First, connect the Arduino board and breadboard. Connect the ultrasonic sensor to the Arduino and provide the required VCC and GND connections. Connect the Trig and Echo pins to suitable digital pins. Connect the buzzer to a digital output pin and GND. Connect the servo motor to a suitable digital pin along with its power and ground connections. Upload the Arduino program using the Arduino IDE. Place an object in front of the ultrasonic sensor and observe the system. When the obstacle enters the 20–50 cm range, the buzzer gives an alert and the servo motor moves the gate to the closed position.

## **5\. Working Principle**

The ultrasonic sensor sends ultrasonic waves and receives the reflected waves from an obstacle. The Arduino calculates the distance based on the time taken for the waves to return.

When the measured distance is between 20 cm and 50 cm, the Arduino activates the buzzer and sends a control signal to the servo motor. The servo motor rotates to close the gate. When no obstacle is detected within the specified range, the system remains in its normal 
![WORKING](WORKING(3).jpg)

## **6\. Applications**

The system can be used as a prototype for **industrial safety gates and restricted-area access barriers**. It can also be adapted for:

* Automatic parking barriers  
* Machine safety zones  
* Restricted-area protection  
* Automated entrance gates  
* Conveyor safety barriers  
* Smart warehouse safety systems  
* Robotic obstacle-response systems

## **7\. Advantages**

The system provides automatic obstacle detection and gate control. It gives an immediate buzzer alert when an obstacle is detected. The components are simple, low-cost, and easily available. The detection range can be modified according to the application. The system can also be expanded with additional sensors and communication modules.

## **8\. Conclusion**

The Smart Automatic Safety Gate successfully demonstrates how an ultrasonic sensor can be combined with a buzzer and servo motor to create an automatic safety mechanism. The Arduino processes the distance information and responds by generating an alert and closing the gate when an obstacle enters the defined range. This prototype provides a foundation for developing automated safety barriers for industrial and other controlled environments.
![RESULT](RESULT(3).jpg)
 


