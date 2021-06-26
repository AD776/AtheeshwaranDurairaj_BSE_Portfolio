# Phone Controlled Robot Arm
I am working on an Arduino robot arm that is controlled by an Android app of my design using MIT App Inventor.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Atheeshwaran Durairaj | Carlmont High School | Computer Science Engineering | Rising Senior

<img width="603" alt="Servo Diagram" src="https://user-images.githubusercontent.com/78531446/123496354-8d97f680-d5dc-11eb-9767-633a3cb42290.png">

# First Milestone
My first milestone was assembling my robot arm and controlling it from my computer. To accomplish this, I first got two servo motors working using a breadboard, and I programmed the Arduino to rotate the servos to a certain degree taking input from my computer using a serial monitor. I got the servos to work by connecting the servo control signal line or the orange wire in my project to one of the digital PWM pins on the Arduino and the servo power and ground to the power and ground on the Arduino. One of my key learning moments was learning about PWN or Pulse Width Modulation. PWM Control allows a digital signal to replicate an analog voltage. However, with an digital pin, I would have only been able to control on or off, whereas with a PWM pin, I could rotate the servos to a certain position. Then, I built the robot arm from the base to the head and claw of the arm. Finally, I got two more servos working and connected the four servos to the robot arm. By controlling the servo motors, I was able to control the robot arm from my computer.

[![Atheeshwaran's First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1624648357/video_to_markdown/images/youtube---DX1YYnA1vw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=-DX1YYnA1vw "Atheeshwaran's First Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was controlling the robot arm from my phone using the Bluetooth provided by the ESP32. The ESP32 is a microcontroller with integrated Wi-Fi and dual-mode Bluetooth, making it a better alternative to the Arduino Uno board that I previously used in my first milestone. With the ESP32, I first set up a connection between a Bluetooth serial terminal app on my phone and the serial monitor on my computer using an example code. I was able to send and receive String text from the app on my phone. I then implemented this same logic to my program controlling the robot arm. However, one challenge that I faced in my own code was that the String text was not displaying in the serial monitor or would display an integer that I did not input. After researching and seeking advice from my instructors, I discovered that the serial monitor received ASCII integer values of the text I sent from my phone. To resolve this problem, I wrote a separate method to convert the ASCII values into their String equivalents, and I was able to successfully control the robot arm from my phone.

# Third Milestone
My third and final milestone was creating a mobile app using the MIT App Inventor and controlling the robot arm using the app. I connected the
<img width="872" alt="MIT App Inventor Design" src="https://user-images.githubusercontent.com/78531446/123488445-d5128880-d5c4-11eb-9879-e866000080a1.png">
<img width="1440" alt="MIT App Inventor Blocks" src="https://user-images.githubusercontent.com/78531446/123494859-342cc900-d5d6-11eb-8a69-49e627e52013.png">



