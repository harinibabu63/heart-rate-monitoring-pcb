# Heart-rate-monitoring-pcb
PCB-based heart rate monitoring circuit using LDR and LM358 op-amp.
Heart Rate Monitoring Device for Workout

The heart rate monitor is used to measure heartbeats in a minute. It can be useful in many applications like health and fitness. For those who go for workouts daily, it has been easy for them to keep track of their moves and steps with the help of this device. To maintain good health, it is important to do exercise at some target heart rate. This will help in achieving better health recovery. Heart rate is a crucial factor in identifying how intense your workout is. If you are over-exerting during a workout your heart will alert you by telling you your heart rate through this device. There are two ways by which heart rate can be measured:
•	Manual way i.e. by counting the number of pulses passing through a wrist
•	Automatic detection i.e. a sensor that will automatically count the heartbeats
The manual way is not efficient in measuring the heart rate because there are more chances of human error in it while a heart rate monitor is more efficient to keep track of the number of pulses passing through a heart during training.

Working:
In this project, I have designed a heartbeat monitor. This module consists of LDR(Light-dependent resistor), and LM358. The LM358 is a transducer amplifier which means that it will take the electrical signals from your heart and will convert them to digital signals in the form of pulses. Whenever a pulse is detected, this module will turn on the LED. This modulated light is received by the light detector. In LDR, when light falls on the resistor, its resistance changes. As the light intensity increases, resistance decreases. Thus, the voltage drops across the resistor decreases. The LM358 has a comparator that compares the output voltages to threshold voltages. If the output voltage is higher than the threshold it means the intensity is high and vice versa. This is how this device measures the intensity of your workout.

[Specifications of LM358 Op Amplifier](https://github.com/harinibabu63/heart-rate-monitoring-pcb/blob/main/opamp.png)
This IC consists of two high gain amplifiers. The reason for using this IC is that it does not require another independent power supply for the working of each comparator. For a single power supply, it provides input voltages from 3V to 32V while for a dual power supply it provides voltages from 1.5V to 16V. It has a DC gain of 100dB. This IC consists of two input power supplies and one output supply in a comparator. It provides a wide range of power supplies.

[Schematic Diagram](https://github.com/harinibabu63/heart-rate-monitoring-pcb/blob/main/Heart%20rate%20monitoring%20schematic.png)
I have implemented my design on Altium designer. After creating a new project, I have designed the symbols and footprints of each component in a schematic document. In the center, there is an op-amp i.e. LM358, and a header on the left side for battery terminals. Below is the schematic diagram of my design.

[Symbols and Footprints](https://github.com/harinibabu63/heart-rate-monitoring-pcb/blob/main/Footprint(%20Heart%20rate%20monitor).png)
While designing the PCB board it is important to take care of the footprint and dimensions of each component. Footprints should be the same as per component size otherwise your design will not be perfect.

[PCB Design](https://github.com/harinibabu63/heart-rate-monitoring-pcb/blob/main/3D_%20view%20of%20Heart%20Rate%20Monitoring.PNG)
After creating the design in the schematic, I have converted it to the PCB. Where I have designed my board with a specific size and dimensions. This includes the routing of the board on different layers. At this part, I can view the 3d model of my board.





