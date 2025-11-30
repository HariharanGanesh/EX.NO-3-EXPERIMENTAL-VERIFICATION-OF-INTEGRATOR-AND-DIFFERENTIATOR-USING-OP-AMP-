3. ##**EX.NO:
** 3  EXPERIMENTAL VERIFICATION OF INTEGRATOR AND DIFFERENTIATOR USING OP-AMP 
            

     
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
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as,
Vo = - (1/Rf C1 ) ∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.
CIRCUIT DIAGRAM
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 22 28 50_adee2bb5](https://github.com/user-attachments/assets/c308ae4f-2d01-4bbb-9189-94cac91d3c90)


## MODEL GRAPH
![WhatsApp Image 2025-11-30 at 22 30 08_bb4d1679](https://github.com/user-attachments/assets/da0459af-edfe-4991-87cc-fac83e713fd3)




---

## DESIGN

![WhatsApp Image 2025-11-30 at 22 35 47_7644c2ca](https://github.com/user-attachments/assets/93dcd061-4813-4e20-b367-4b3c912c9887)
	

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


## TABULATION
![WhatsApp Image 2025-11-30 at 22 29 23_e12947fd](https://github.com/user-attachments/assets/136dc12f-b6a4-4b6c-a644-5a1fbd10577e)


---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 22 30 36_587266e0](https://github.com/user-attachments/assets/7b3b69a8-4272-41c6-b286-356a4d9c4d07)


---
  
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
![WhatsApp Image 2025-11-30 at 22 26 27_3fcbf18e](https://github.com/user-attachments/assets/7b822737-a72a-456d-b19d-462e2314f60f)



## MODEL GRAPH

![WhatsApp Image 2025-11-30 at 22 27 24_049e0561](https://github.com/user-attachments/assets/af756539-f5a1-4fcf-af18-eebe6527a41b)



---

## DESIGN

![WhatsApp Image 2025-11-30 at 22 34 30_b68d18fe](https://github.com/user-attachments/assets/1c3ba8cb-f527-44a3-8af7-1159c4c50cd3)



## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

 ## TABULATION
![WhatsApp Image 2025-11-30 at 22 26 56_af72db57](https://github.com/user-attachments/assets/7f6ae92c-c4e7-413c-a581-dcd75d51c87a)

		

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-30 at 22 27 56_4360a14d](https://github.com/user-attachments/assets/cf994634-5d23-4cf5-b762-5b688e958dd5)
![WhatsApp Image 2025-11-30 at 22 28 28_3902a6e0](https://github.com/user-attachments/assets/cba1aed2-c2c9-44c3-8a66-732a2671e283)


RESULT:
Thus an Integrator and Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.
---



