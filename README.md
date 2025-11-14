# EXPT-5-DESIGN-OF-ACTIVE-LOW-PASS-HIGH-PASS-AND-BAND-PASS-FILTERS-USING-OP-AMP

# AIM:

To design and obtain the frequency response of
i) First order Low Pass Filter (LPF)
ii) First order High Pass Filter (HPF)
iii) Band pass filter

# APPARATUS REQUIRED:
<img width="951" height="255" alt="image" src="https://github.com/user-attachments/assets/0be75f46-a2db-4722-bc15-3e26cf590cd0" />

# THEORY:
# LOW PASS FILTER

A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.

# CIRCUIT DIAGRAM: LOW PASS FILTER
<img width="535" height="292" alt="image" src="https://github.com/user-attachments/assets/0efc7257-2117-4c25-b231-9811d694566a" />

# MODEL GRAPH:
<img width="586" height="359" alt="image" src="https://github.com/user-attachments/assets/429258e6-e209-49ea-9b47-38a835a30253" />

# DESIGN:
Design a second oder Butterworth filter with thw upper cutoff frequency of 1KHz.
![WhatsApp Image 2025-11-14 at 16 22 42_fe8995d1](https://github.com/user-attachments/assets/43a703b4-0bda-410e-9691-bb591f4f63f7)

# TABULATION:
![WhatsApp Image 2025-11-14 at 16 20 04_9ce4f132](https://github.com/user-attachments/assets/2833f15f-ac74-4754-84a0-4d200d37bfad)

# GRAPH:
![WhatsApp Image 2025-11-14 at 16 23 07_05e32cf6](https://github.com/user-attachments/assets/85ac760c-f5e4-4f2e-9165-c007945a1a57)

# THEORY:
# HIGH PASS FILTER

A LPF allows frequencies from 0 to higher cut of frequencThe frequency at which the magnitude of the gain is 0.707 times the maximum value of gain is called low cut off frequency. Obviously, all frequencies higher than fL are pass band frequencies with the highest frequency determined by the closed –loop band width all of the op- amp.

# CIRCUIT DIAGRAM: HIGH PASS FILTER
<img width="533" height="314" alt="image" src="https://github.com/user-attachments/assets/1090306e-34c0-45db-8250-ad354d83d83b" />


# MODEL GRAPH:
<img width="695" height="337" alt="image" src="https://github.com/user-attachments/assets/5b67fa34-f791-4cf2-a4aa-b139eb9bba51" />


# DESIGN:
Design a second oder Butterworth filter with thw lower cutoff frequency of 1KHz.

![WhatsApp Image 2025-11-14 at 16 22 42_0c5b7b4d](https://github.com/user-attachments/assets/e03a37c6-797b-4084-a202-43a0f9ddbf22)

# TABULATION:
![WhatsApp Image 2025-11-14 at 16 22 03_6a9b04f9](https://github.com/user-attachments/assets/21ef0670-5f9b-4411-8c12-b5fe35159585)

# GRAPH:
![WhatsApp Image 2025-11-14 at 16 22 23_e64ecc0a](https://github.com/user-attachments/assets/0d53b143-3cce-4df0-8205-936e3d158a0f)

# THEORY:
# BAND PASS FILTER

A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > fL. Any input frequency outside this pass band is attenuated. There are two types of band-pass filters. Wide band pass and Narrow band pass filters. We can define a filter as wide band pass if its quality factor Q <10. If Q>10, then we call the filter a narrow band pass filter. A wide band pass filter can be formed by simply cascading high-pass and low-pass sections. The order of band pass filter depends on the order of high pass and low pass sections.

# CIRCUIT DIAGRAM: BAND PASS FILTER
<img width="602" height="257" alt="image" src="https://github.com/user-attachments/assets/89b232eb-3bc6-4784-bad4-bf40f78031ed" />

# MODEL GRAPH:
<img width="1037" height="460" alt="image" src="https://github.com/user-attachments/assets/052fae74-cf20-4911-bbe6-92cf576a1b63" />


# DESIGN:
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
![WhatsApp Image 2025-11-14 at 16 22 42_d62f2a14](https://github.com/user-attachments/assets/d28e6944-5073-4bd1-a245-62fe4688be9d)

# TABULATION:
![WhatsApp Image 2025-11-14 at 16 23 23_f8535373](https://github.com/user-attachments/assets/1bab2e08-2f86-4894-bce8-9f5a542e5d00)

# GRAPH:
![WhatsApp Image 2025-11-14 at 16 23 41_8c9aec35](https://github.com/user-attachments/assets/26a4fd18-e1e6-41f5-a368-fa54892b46be)

# PROCEDURE - (LPF & HPF):
1. Connect the circuit as shown in the circuit diagram.
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4. Tabulate the output voltage Vo with respect to different values of input frequency.
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.

# PROCEDURE:BAND PASS FILTER
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3. Connect the circuit as shown in the circuit diagram.
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5. Tabulate the output voltage Vo with respect to different values of input frequency.
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.


# RESULT
![WhatsApp Image 2025-11-14 at 16 24 00_bb67d248](https://github.com/user-attachments/assets/43f8e969-389d-4027-92fe-5cd281aaaae0)
