# **Portfolio**
## About myself
I am a 5th grade student in the Robotica y Sistemas Digitales degree taught by Tecnologico de Monterrey in Mexico City campus. 
I am interested in the fields of computer physics in the part of fluid physics. But my main interest is in biomechanics to apply robotics in medical applications and help people to gain back mobility.

## Projects
### [*Linear Movement Controller for a model car*](https://youtu.be/JyiAmCLHmWY)
In this project I designed a linear control system for a scale car. My main contribution to the project was the implementation of the CAN bus protocol so that the system can communicate with other controllers through a channel using CAN messages, the objective of using a CAN protocol is to give the system a way to communicate with other controllers conected to the same bus, this allow to share information for feedback or to modify the parameters.
The way I implemented this system is by using a CAN tranceiver that translated the message am sending from the microncontroller that is being used in the system to a message that can travel through the CAN bus. When this message arrives to its destiny it joins the CAN message to the format accepted by the objective microcontroller. In this case the objective microcontroller is a ESP32 that receives the message. Then I created a hotspot in my cellphone to which the ESP32 connected to. I designed a dashboard with the Arduino IoT tool with which I can read the CAN messages that arrive at the esp32 in order to gain feedback on how the system is working and detect possible flaws. In the same way by using this dashaboard I can send CAN messages back to the system to change the linear velocity I wish the system follows.
I also helped to calculate the values of the controller that is used by making a vibration analysis with FFT. This by using a program in MATLAB which received the accelerations from an acceleration sensor that is attached to the car, after gaining this information I used the MATLAB's library System Identifation to obtain the transfer function that describes how the system works, when I considered I got a good enough function I used the library PID Tuner to tune values that allow the system to behave the way I want.
[![video:](https://img.youtube.com/vi/JyiAmCLHmWY/0.jpg)](https://www.youtube.com/watch?v=JyiAmCLHmWY)
### [*Fridge system to detect if the freezer were not close for a long period*](https://youtu.be/n9J0cujmhg0)
[![video:](https://img.youtube.com/vi/n9J0cujmhg0/0.jpg)](https://www.youtube.com/watch?v=n9J0cujmhg0)
