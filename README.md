# GUI-Based FIR Audio Filter

This project is a **MATLAB GUI application** for performing **FIR (Finite Impulse Response) audio filtering** and noise removal.  
It allows users to load or record an audio signal, apply different types of FIR filters, and visualize the results in both time and frequency domains.

---

## 🎛️ Features

- **Load or Record Audio** directly from the GUI  
- **Four FIR filter types**: Lowpass, Highpass, Bandpass, and Bandstop  
- Adjustable **cutoff frequencies** and **filter length**  
- **Real-time visualization** of:
  - Time domain signal  
  - Frequency spectrum  
  - Magnitude response  
  - Phase response  
- **Play original and filtered audio** within the GUI  
- **Save the filtered output** as a `.wav` file  

---

## ⚙️ How to Run

1. Open MATLAB.  
2. Place the file `audio_filter_gui_fir_sidebar.m` in your working directory.  
3. In the Command Window, run:
   ```matlab
   audio_filter_gui_fir_sidebar
