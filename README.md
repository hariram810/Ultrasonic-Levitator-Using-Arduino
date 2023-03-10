# Ultrasonic-Levitator-Using-Arduino

![Screenshot (759)](https://user-images.githubusercontent.com/118633170/209069010-b4453bc1-968d-4561-a3c0-289614b8e53a.png)


If you have hard-time 3d printing stuff and other materials which i have provided in this project please refer the professionals for the help, [JLCPCB](https://jlcpcb.com/RNA) is one of the best company from shenzhen china they provide, PCB manufacturing, PCBA and 3D printing services to people in need, they provide good quality products in all sectors

[JLCPCB](https://jlcpcb.com/RNA)


Please use the following link to register an account in [JLCPCB](https://jlcpcb.com/RNA)

https://jlcpcb.com/RNA


Pcb Manufacturing

----------

2 layers

4 layers

6 layers

jlcpcb.com/RNA



PCBA Services

[JLCPCB](https://jlcpcb.com/RNA) have 350k+ Components In-stock. You don’t have to worry about parts sourcing, this helps you to save time and hassle, also keeps your costs down.

Moreover, you can pre-order parts and hold the inventory at [JLCPCB](https://jlcpcb.com/RNA), giving you peace-of-mind that you won't run into any last minute part shortages. jlcpcb.com/RNA


3d printing

-------------------

SLA -- MJF --SLM -- FDM -- & SLS. easy order and fast shipping makes [JLCPCB](https://jlcpcb.com/RNA) better companion among other manufactures try out [JLCPCB](https://jlcpcb.com/RNA) 3D Printing servies

[JLCPCB](https://jlcpcb.com/RNA) 3D Printing starts at $1 &Get $54 Coupons for new users

![Screenshot (760)](https://user-images.githubusercontent.com/118633170/209069080-1b6924a2-61d8-4dc4-bbd9-b486b46f41f8.png)


To understand how acoustic levitation works, you first need to know a little about gravity, air and sound. First, gravity is a force that causes objects to attract one another. An enormous object, like the Earth, easily attracts objects that are close to it, like apples hanging from trees. Scientists haven't decided exactly what causes this attraction, but they believe it exists everywhere in the universe.

Second, the air is a fluid that behaves essentially the same way liquids do. Like liquids, air is made of microscopic particles that move in relation to one another. Air also moves like water does -- in fact, some aerodynamic tests take place underwater instead of in the air. The particles in gasses, like the ones that make up air, are simply farther apart and move faster than the particles in liquids.


![Screenshot (761)](https://user-images.githubusercontent.com/118633170/209069091-4858296b-b95f-455b-a760-57c8ca67efbb.png)
![Screenshot (762)](https://user-images.githubusercontent.com/118633170/209069097-0b9b9a77-fe52-46b9-8a5f-aafd0f67f094.png)

In contrast to magnetic levitation, the ultrasound method does not require a control loop to stabilize the hovering object. Using acoustic levitation, the object simply lodges itself into one of the nodes of a standing acoustic wave. And you can make multiple items hover on top of one another simultaneously, evenly spaced apart!

In our 2/18 issue of Make: German edition, we published two alternative approaches to ultrasonic levitation devices, one of them based on a transducer taken from a gutted ultrasonic cleaner.This project is based on ultrasonic transducers of the kind used in distance sensors such as the HC-SR04 module, which can be sourced from eBay for less than $2

These modules contain one transducer operating as a transmitter (T), and another serving as a receiver (R). In principle, the T transducer is the better pick for use as an actual transmitter, so we bought two sensors and pulled the T transducers off each of them. (In a pinch, you could buy just one sensor — the R transducer also transmits well Desolder both transmitter transducers. While you’re at it, disassemble one of the receiver transducers. Please don’t throw away the small, wire screen from the receiver— it turns out to be unexpectedly useful.

![Screenshot (763)](https://user-images.githubusercontent.com/118633170/209069108-7c43e3b9-b6b6-40d2-80f1-be9bfc2c040c.png)
![Screenshot (764)](https://user-images.githubusercontent.com/118633170/209069119-b994f401-0cef-413a-a104-5249fec485aa.png)


The transducers are designed to operate at 40kHz, the frequency at which they work most efficiently. That signal will be generated by your Arduino Nano.

Third, the sound is a vibration that travels through a medium, like a gas, a liquid or a solid object. if you strike a bell, the bell vibrates in the air. As one side of the bell moves out, it pushes the air molecules next to it, increasing the pressure in that region of the air. This area of higher pressure is a compression. As the side of the bell moves back in, it pulls the molecules apart, creating a lower-pressure region called a rarefaction. Without this movement of molecules, the sound could not travel, which is why there is no sound in a vacuum.

acoustic levitator

A basic acoustic levitator has two main parts -- a transducer, which is a vibrating surface that makes the sound, and a reflector. Often, the transducer and reflector have concave surfaces to help focus the sound. A sound wave travels away from the transducer and bounces off the reflector. Three basic properties of this travelling, reflecting wave help it to suspend objects in midair.

![Screenshot (768)](https://user-images.githubusercontent.com/118633170/209069134-ef7ae2bb-5049-4463-bff1-1bd21412c041.png)
![Screenshot (769)](https://user-images.githubusercontent.com/118633170/209069136-2df45183-0f39-4a46-8ef1-412f3319a3dc.png)


when a sound wave reflects off of a surface, the interaction between its compressions and rarefactions causes interference. Compressions that meet other compressions amplify one another, and compressions that meet rarefactions balance one another out. Sometimes, reflection and interference can combine to create a standing wave. Standing waves appear to shift back and forth or vibrate in segments rather than travel from place to place. This illusion of stillness is what gives standing waves their name.Standing sound waves have defined nodes, or areas of minimum pressure, and antinodes, or areas of maximum pressure. A standing wave's nodes are at the reason of acoustic levitation.

By placing a reflector the right distance away from a transducer, the acoustic levitator creates a standing wave. When the orientation of the wave is parallel to the pull of gravity, portions of the standing wave have a constant downward pressure and others have constant upward pressure. The nodes have very little pressure.

the working principle of the circuit is very simple. The main component of this project is an Arduino, L298 motor driving IC, and ultrasonic transducer collected from the ultrasonic sensor module HCSR04. Generally, the ultrasonic sensor transmits an acoustic wave of a frequency signal between 25khz to 50 kHz, and in this project, we are using HCSR04 ultrasonic transducer. This ultrasonic waves makes the standing waves with nodes and antinodes.

![Screenshot (772)](https://user-images.githubusercontent.com/118633170/209069150-893fd64b-d716-40f3-a87b-1a1632d6ed86.png)
![Screenshot (771)](https://user-images.githubusercontent.com/118633170/209069160-2898be0e-efe8-443f-9e9d-d33aa33d068f.png)


this ultrasonic transducer’s working frequency is 40 kHz. So, the purpose of using Arduino and this small piece of code is to generate a 40KHz high-frequency oscillation signal for my ultrasonic sensor or transducer and this pulse is applied to the input of duel motor driver IC L293D (from Arduino A0 & A1 pins) to drive the ultrasonic transducer. Finally, we apply this high-frequency 40KHz oscillation signal along with driving voltage through driving IC (typically 7.4v) on the ultrasonic transducer. As a result of which ultrasonic transducer produces acoustic sound waves. We placed two transducers face to face in the opposite direction in such a manner that some space is left between them.

![Screenshot (773)](https://user-images.githubusercontent.com/118633170/209069181-b5495f54-cca5-420f-9fce-e4052775d4c9.png)


Making the Transducer
First we need to desolder the transmitter and receiver from ultrasonic module. Also remove the protective cover then connect long wires to it. Then place the transmitter and receiver one over the other remember, the position of ultrasonic transducers is very important. They should face each other in the opposite direction which is very important and they should be in the same line so that ultrasonic sound waves can travel and intersect each other in opposite directions. For this i used foam sheet ,nuts and bots

Important Things and Improvements


The placement of transducer is very Important so try to place that in proper postion

We can lift only small pieces of lightweight objects like thermocol and paper

Should provide atleast 2 amp current

Next i tried to to levitate big objects for that first i increase the no. Of transmittors and recivers that didint work. So next i tried with high voltage thats also failed.

Improments

Later i understood i failed because of the. Arrangement of transducers if we use multiple transmitters then we should alian in a Curvy structure.

![Screenshot (765)](https://user-images.githubusercontent.com/118633170/209069204-88cbb655-ad9a-4fa4-b40c-32e8274c345d.png)
![Screenshot (766)](https://user-images.githubusercontent.com/118633170/209069209-8419d330-e421-4518-9175-e61fee49d797.png)


byte TP = 0b10101010; // Every other port receives the inverted signalvoid setup() { DDRC = 0b11111111; // Set all analog ports to be outputs // Initialize Timer1 noInterrupts(); // Disable interrupts TCCR1A = 0; TCCR1B = 0; TCNT1 = 0; OCR1A = 200; // Set compare register (16MHz / 200 = 80kHz square wave -> 40kHz full wave) TCCR1B |= (1 << WGM12); // CTC mode TCCR1B |= (1 << CS10); // Set prescaler to 1 ==> no prescaling TIMSK1 |= (1 << OCIE1A); // Enable compare timer interrupt interrupts(); // Enable interrupts}ISR(TIMER1_COMPA_vect) { PORTC = TP; // Send the value of TP to the outputs TP = ~TP; // Invert TP for the next run}void loop() { // Nothing left to do here :)}
