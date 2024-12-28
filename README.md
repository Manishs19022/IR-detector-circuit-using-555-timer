# IR-detector-circuit-using-555-timer
To design and simulate a IR detector circuit using 555 timer


# MULTISIM APPARATUS:

1.	555 Timer IC

2.	IR Transmitter

3.	IR Receiver

4.	BC547 transistor

5.	BC557 transistor


6.	10 uF/25V Capacitor

7.	Led

8.	Resistor (1 KΩ, 10 KΩ, 22 KΩ, 220Ω) 

9.	Piezo Buzzer, switch & battery


# CIRCUIT DIAGRAM:

![image](https://github.com/user-attachments/assets/8d299570-4464-44d4-82cd-56b3fc653108)


# Circuit Connection:

In this IR sensor project, we will put the IC 555 timer IC on the breadboard. And then we should connect pin 8 to the collector of the BC557 transistor and pin 1 to the ground. Next, the base of BC557 is connected to the collector of the BC547 transistor through a 1 KΩ resistor. Another terminal of BC557 i.e., the emitter is directly connected to Vcc.

The base of the BC547 is connected between the cathode of the IR receiver and a 10 KΩ resistor. And another emitter part is connected directly to the ground.

Next, Pin 7 of the IC is connected between a 1 KΩ and a 22 KΩ resistor and it is connected with pin 6 through this 22 KΩ resistor. 

Pin 6 and pin 2 are connected with each other and a 10uF capacitor from pin 6 is connected to the ground.

Finally, the IR receiver is connected to the base terminal of BC547 with its cathode terminal this terminal is also connected to the ground through a 10 KΩ resistor. Its anode terminal is connected to Vcc. 

The IR transmitter is connected with Vcc with its cathode terminal and the anode terminal is connected to the ground through a 220 Ω resistor. The output from pin 3 of the IC is connected to a buzzer and another terminal of the buzzer is grounded.


# Working principle of IR Sensor:

In the above IR sensor circuit diagram, we should note that transistor BC547 is an NPN transistor and transistor BC557 is a PNP transistor. BC547 will be in an active mood when a positive voltage is applied to its base and the BC557 will be in an active mood when a negative voltage is applied to its base. 


When the whole circuit is turned on, the IR transmitter starts emitting infrared rays, which fall on the IR receiver and a potential difference will create across the IR receiver which turns on the transistor BC547, which further turns on the transistor BC557 through the collector and base. Then the transistor BC557 starts to conduct Vcc supply to pin 8 of the 555 timer IC which turns on the 555 timer IC.


In this IR sensor project, the 555 timer IC is configured in astable mode. The output from pin 3 by turning on the circuit which is shown by a buzzer is activated for a particular frequency. This frequency of the buzzer’s beeping can be determined by the given formula 


Output Frequency = 1.44/(R1+2*R2)*C1


Where R1 represents the resistor between pin 7 and pin 8 i.e., 1 KΩ resistor and R2 represents the resistor between pin 6 and pin 7 i.e., 22 KΩ resistors. C1 represents the capacitor between pin 6 and the ground of the 555 timers IC i.e., 10 uF.


# RESULTS:

The experiment successfully achieved its objectives by thoroughly examining the IR detector circuit using 555 timers.


# CONCLUSION:

The DIY IR sensor with a 555 timer offers a cost-effective and versatile solution for various projects. Its simplicity, adjustability, and educational value make it an ideal choice for beginners exploring electronics. While suitable for many applications, consideration of specific project requirements is essential.














