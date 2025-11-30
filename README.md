3. ##**EX.NO:
** 3  EXPERIMENTAL VERIFICATION OF INTEGRATOR AND DIFFERENTIATOR USING OP-AMP 
            
**DATE:**  
             3A INTEGRATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
INTEGRATOR
INTEGRATOR A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as, Vo = - (1/Rf C1 ) ∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is, T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits. CIRCUIT DIAGRAM


Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.
CIRCUIT DIAGRAM
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 22 28 50_55acd070](https://github.com/user-attachments/assets/6950464b-b8ad-4364-83e6-166ba5b4446b)



## MODEL GRAPH
![WhatsApp Image 2025-11-30 at 22 30 08_28d6f0b4](https://github.com/user-attachments/assets/8339e6b1-ce65-4b1d-9c70-03e7006e1f71)

---

## DESIGN

![WhatsApp Image 2025-11-30 at 22 35 47_b4bdeb5f](https://github.com/user-attachments/assets/68565674-e97a-4d9d-832a-41dee59bb0b9)

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


![WhatsApp Image 2025-11-30 at 22 29 23_6aaf68ff](https://github.com/user-attachments/assets/f3a64bac-cc6a-46eb-863f-54c9684411b9)

		

---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 22 30 36_0f5fc6f8](https://github.com/user-attachments/assets/518c7614-696d-40d0-b6e2-8058a942bdb4)


---
**DATE:**  
             3 B DIFFERENTIATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,
Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1.	Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 µF, calculate the value of Rf.
2.	Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.

The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 22 26 27_156f6830](https://github.com/user-attachments/assets/e92182a3-a5e0-46ce-80a9-c4fec3c4754e)




## MODEL GRAPH

![WhatsApp Image 2025-11-30 at 22 27 24_50a2dc04](https://github.com/user-attachments/assets/615b3fc9-9854-46ba-856f-167d090bd5f9)

---

## DESIGN

![WhatsApp Image 2025-11-30 at 22 34 30_a1e9467a](https://github.com/user-attachments/assets/a01250e5-51af-466e-87b1-ed4782aa3624)



## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

##TABUATION
![WhatsApp Image 2025-11-30 at 22 26 56_c0659f9c](https://github.com/user-attachments/assets/ebe4284a-72ec-4d10-822f-8d27aef8fb39)
		

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 22 27 56_1b7979df](https://github.com/user-attachments/assets/e33d9bbe-60a6-4c61-a476-da1b440093f6)
![WhatsApp Image 2025-11-30 at 22 28 28_2ad3915a](https://github.com/user-attachments/assets/d197d2c2-c585-4fbf-b1da-513a11d93730)

---

RESULT:
Thus an Integrator and Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.
---



