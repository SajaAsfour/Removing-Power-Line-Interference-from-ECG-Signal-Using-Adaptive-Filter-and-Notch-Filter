# 🏥 Removing Power Line Interference from ECG Signals

## 📌 Overview
This repository contains my implementation of **Power Line Interference Removal from ECG Signals** for the **ENCS4310: Digital Signal Processing (DSP)** course at **Birzeit University**. The project compares different filtering techniques—**Notch Filter, NLMS Adaptive Filter, RLS Adaptive Filter, and Extended Kalman Filter (EKF)**—to eliminate **50 Hz power line noise** from ECG signals.

## 🛠 Features
- ✅ **Filtering Techniques Implemented:**
  - Notch Filter (Traditional Method)
  - Adaptive Filters (NLMS & RLS)
  - Extended Kalman Filter (EKF)
- ✅ **Performance Metrics:**
  - Signal-to-Noise Ratio (SNR)
  - Percentage Root Mean Square Difference (PRD)
  - Mean Square Error (MSE)
- ✅ **Time and Frequency Domain Analysis**
- ✅ **Power Spectral Density (PSD) & Spectrogram Visualization**
- ✅ **Evaluation Using MIT-BIH ECG Dataset**

## 📂 Contents
- 📜 **MATLAB Code:** Implementation of all filtering techniques.
- 📊 **Results & Analysis:** Performance comparison of different filters.
- 📄 **Report:** Detailed discussion on methods, results, and conclusions.
- 📈 **Plots & Spectrograms:** Graphical analysis of filtered ECG signals.

## 📌 Results Summary
- **Best Performing Filter:** The **Notch Filter** achieved the highest SNR (24.75 dB), lowest PRD (6.225%), and lowest MSE (29.8), making it the best choice for ECG denoising.
- **Adaptive NLMS Filter:** Provides a good balance between noise suppression and signal integrity.
- **RLS & EKF Filters:** Less effective in performance compared to the Notch and NLMS filters.

## 📌 Requirements
- MATLAB
- Signal Processing Toolbox
- MIT-BIH ECG Dataset

## 👩‍💻 Authors
**Saja Asfour**
- 🎓 Computer Engineering Student at Birzeit University
- 🏠 GitHub: [SajaAsfour](https://github.com/SajaAsfour)

**Yara Khattab** 
- 🎓 Computer Engineering Student at Birzeit University
- 🏠 GitHub: [yarakhattab](https://github.com/yarakhattab)
- 
**Rawand Bawatneh**
- 🎓 Computer Engineering Student at Birzeit University
- 🏠 GitHub: [rawandbawatneh](https://github.com/rawandbawatneh)

## 📜 License
This repository is for educational purposes. Feel free to use and reference the work, but please give proper credit. 😊
