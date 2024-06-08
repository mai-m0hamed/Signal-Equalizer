# Signal Equalizer Desktop Application
## Team 4

1. **Sondos Mahmoud**
2. **Fatma Ehab**
3. **Mai Mohamed**
4. **Noura Osama**
## Overview

Signal Equalizer is a Python desktop application built using PyQt5 that serves as a fundamental tool in the music and speech industry. It finds applications in various fields, including biomedical use for hearing aid abnormalities detection.

## Description

The application enables users to open a signal and adjust the magnitude of specific frequency components using sliders, subsequently reconstructing the modified signal. It offers multiple working modes:

1. **Uniform Range Mode:**
   - Divides the total frequency range of the input signal into 10 equal ranges, each controlled by a dedicated slider in the UI.

     
![image](https://github.com/mai-m0hamed/Signal-Equalizer/assets/115077795/6e57bfdb-720c-4e62-86bd-9113db447182)



2. **Musical Instruments Mode:**
   - Allows each slider to control the magnitude of a specific musical instrument in the signal.
     
![image](https://github.com/mai-m0hamed/Signal-Equalizer/assets/115077795/2d799e9d-139a-4be0-9c8c-810a6022a7e3)

3. **Animal Sounds Mode:**
   - Permits each slider to control the magnitude of specific animal sounds in a mixture of frequencies.

     
![image](https://github.com/mai-m0hamed/Signal-Equalizer/assets/115077795/7f0b617c-3a82-4841-b623-d004afc5601f)


4. **ECG Abnormalities Mode:**
   - Empowers each slider to control the magnitude of arrhythmia components in the input signal.


![image](https://github.com/mai-m0hamed/Signal-Equalizer/assets/115077795/f4f60a20-0ff7-41b6-87de-f5653bd3deb6)


In addition, the application employs four multiplication/smoothing windows (Rectangle, Hamming, Hanning, Gaussian) when multiplying the frequency range with the corresponding slider value.


![image](https://github.com/mai-m0hamed/Signal-Equalizer/assets/115077795/21dbce67-e6ac-470a-8897-61f611b4188a)

Users can easily switch between modes through a combobox in the UI.



## Features

- **Cine Signal Viewers:**
  - Two linked cine signal viewers for input and output signals.
  - Full set of functionality panel (play/stop/pause/speed-control/zoom/pan/reset) respecting all boundary conditions.
  - Synchronous playback of signals in time.

- **Spectrograms:**
  - Two spectrograms for input and output signals.
  - Real-time reflection of changes made through equalizer sliders.
  - Option to toggle show/hide of the spectrograms.




