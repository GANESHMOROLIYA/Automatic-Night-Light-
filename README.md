# Automatic-Night-Light-

we made this project in engineering 2nd year 3rd sem in electronics devices subject


automatic night lamp circuit diagram using LDR and LM358 OPAMP which automatically turns the LEDs ON at night and OFF when it is daytime. The sensing part which is being used for detecting the light is a Light Dependent Resistor (LDR). The resistance of LDR depends on the light incident on it. The greater the light, the lower will be the resistance. We are using a relay to control an AC lamp


![image](https://github.com/GANESHMOROLIYA/Automatic-Night-Light-/assets/158822512/b40ed4b2-3fed-495d-8fc5-654c2d714cdd)



Components Required for Automatic Night Lamp:
R1 LDR (light dependent Resistor)
RP1 10k potentiometer
R2 22k
R3 10k
Q1 BC547 (NPN Transistor)
1N4148 Diode
12V Relay SPDT
LM358 OPAMP
Bulb



Working of Automatic Night Lamp Circuit:
The working of the circuit is simple. OPAMP LM358 is used to switch the input of the transistor from high to low. The transistor is used as a switch to control the 12V relay module. When there is no light (at night), the resistance of LDR will increase. The voltage across LDR will increase, this voltage is applied at the non-inverting terminal of the opamp. When it reaches a voltage that is greater than the voltage at the inverting terminal of opamp output goes high. Transistor Q1 will turn ON, it will drive the relay. The relay will turn ON and it will switch the AC light bulb making glow.
