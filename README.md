# GENERATION-AND-DETECTION-OF-FM---USING---SCILAB
# FREQUENCY MODULATION AND DEMODULATION

## AIM

To write a program for Frequency Modulation and Demodulation using SCILAB and to observe and measure the frequency deviation and the modulation index of FM.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

---

## THEORY

Frequency modulation is a type of modulation in which the frequency of the high frequency (carrier) is varied in accordance with the instantaneous value of the modulating signal.

### FREQUENCY DEVIATION Δf and MODULATION INDEX mf:

The frequency deviation **Δf** represents the maximum shift between the modulated signal frequency, over and under the frequency of the carrier.

We define modulation index **mf** the ratio between **Δf** and the modulating frequency.

$$
m_f = \frac{\Delta f}{f_m}
$$

---

## FREQUENCY MODULATION GENERATION

The circuits used to generate a frequency modulation must vary the frequency of a high frequency signal (carrier) as function of the amplitude of a low frequency signal (modulating signal). In practice there are two main methods used to generate FM.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the modulating signal.
* **Beta:** Modulation index, which controls the extent of frequency deviation.

### 2. Generate Signals:

* **modulating_signal:** Sinusoidal signal used for modulation.
* **carrier_signal:** The high-frequency carrier signal.
* **modulated_signal:** FM modulated signal calculated by varying the carrier frequency according to the modulating signal.

### 3. FM Modulation:

* **Modulated_signal** is obtained by modulating the carrier signal with the modulating signal.

### 4. FM Demodulation:

* **Differentiation:** Computes the derivative of the modulated signal to extract frequency variations.
* **Envelope Detection:** Takes the absolute value to retrieve the envelope of the signal.
* **Low-pass Filtering:** Applies a Butterworth low-pass filter to smooth the envelope and recover the original modulating signal.

### 5. Visualization:

* Plots the modulating signal, carrier signal, FM modulated signal, and demodulated signal for analysis.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## Tabulation
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/4c7db640-ec63-4b99-a082-c5bda13d5497" />




## Output
<img width="961" height="1600" alt="image" src="https://github.com/user-attachments/assets/45d8685b-17f2-4306-ae3d-7792b9e1cb6f" />
MARK SPLIT-UP:
<img width="1406" height="658" alt="image" src="https://github.com/user-attachments/assets/0e4b24e8-a9ef-415b-8d4c-77aa0d2faf22" />



## Result
<img width="1522" height="457" alt="image" src="https://github.com/user-attachments/assets/d3912cc3-c4a2-48ca-a6bd-fc2adcdb2257" />







