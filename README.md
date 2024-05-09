# **Portfolio**
## About myself
I am a 5th grade student in the Robotica y Sistemas Digitales degree taught by Tecnologico de Monterrey in Mexico City campus. 
I am interested in the fields of computer physics in the part of fluid physics. But my main interest is in biomechanics to apply robotics in medical applications and help people to gain back mobility.
Sujeto-Verbo-Complemento
## Projects
### [*Linear Movement Controller for a downscaled car*](https://youtu.be/JyiAmCLHmWY)
My main contribution to the project was the implementation of the CAN bus protocol. By using this protocol the system can comunicate information with other subsystems that share the same bus.
A tranceiver were used to translate from a format compatible with the system controller to a format that can travell through the CAN bus. When the CAN message arrived to an objective subsystem it was translated back to a format that the said subsystem can understand. In the case of this system the objective  subsystem was an ESP32 microcontroller. The ESP32 microcontroller connected to a mobile hotspot to transmit the messages via Wi-Fi to an Arduino IoT app. A dashbboard were designed to receive information on how the system is working and detect possible errors. It also allowed me to send a desired linear velocity to the system.
I also helped in obtaining the values for the PID controller that controlled the system. This by obtaining the transfer function that described the system with the help of MATLAB's library System Identification. After obtaining a good enough transfer function the data was sent to MATLAB's PID Tuner to calculate the control values.

[![video:](https://img.youtube.com/vi/JyiAmCLHmWY/0.jpg)](https://www.youtube.com/watch?v=JyiAmCLHmWY)
### [*Fridge system to detect if the freezer were not close for a long period*](https://youtu.be/n9J0cujmhg0)
[![video:](https://img.youtube.com/vi/n9J0cujmhg0/0.jpg)](https://www.youtube.com/watch?v=n9J0cujmhg0)
