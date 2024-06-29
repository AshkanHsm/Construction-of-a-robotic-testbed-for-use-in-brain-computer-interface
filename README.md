# Construction-of-a-robotic-testbed-for-use-in-brain-computer-interface

In brain-computer interface systems, the movement of an external system such as a robot can be controlled with the help of analysis of the neural signals collected from the brain. Here, we seek to use steady-state evoked potential to visual stimulation to control the movement of a robotic arm. This process is divided into two parts; in the first part, the preparation of the platform required for visual stimulation and the collection and analysis of EEG data is done. In the second part, which is the subject of this project, a robotic test platform is built to receive the results of neural signal analysis and perform several different movements.

This robotic test platform includes a data transfer interface, a processor, and a robotic mechanism along with actuators and sensors. After the EEG data is analyzed, according to the type of stimulation, a motion command is sent to the robotic system through the data transmission interface. This system receives the command as a reference input and performs the proportional movement in a closed control loop. This command can be a back-and-forth movement in two different axes. The robotic platform can be a two-axis gimbal for controlling the camera angle, a two-axis robotic arm, or an upper body exoskeleton.
