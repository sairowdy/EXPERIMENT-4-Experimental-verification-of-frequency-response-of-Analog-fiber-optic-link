
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="1064" height="642" alt="image" src="https://github.com/user-attachments/assets/4b433ac3-30b4-4c98-a320-988e32ea11f5" />


## CONNECTION DIAGRAM  
**Setting up an Analog Link**
## TABULATION  

<img width="721" height="1280" alt="image" src="https://github.com/user-attachments/assets/357198bc-8dc0-4876-bbe8-bbfe0026c8d2" />

## MODEL GRAPH

<img width="751" height="367" alt="image" src="https://github.com/user-attachments/assets/8abd77e4-cf2c-46b8-92b0-bd4ce0a6c06c" />

# Output:

<img width="1600" height="1205" alt="image" src="https://github.com/user-attachments/assets/8bd4a749-7d98-4cd4-bb8a-d567d024bbea" />

## RESULT

Thus, the relationship between input and received output signal from 660nm fibre optic cable using analog link is analyzed
