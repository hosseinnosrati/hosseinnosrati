# Hi, I'm H. Nosrati 👋

**Electrical & Telecommunications Engineer | Digital Signal Processing (DSP) | Edge AI & Biosensing**

I specialize in designing deterministic, resource-constrained **Digital Signal Processing (DSP)** and **Edge Computing** pipelines for wearable healthcare devices, wireless sensing, and real-time audio systems. My work focuses on bridging statistical signal processing theory with bare-metal embedded firmware execution.

---

### 🔬 Technical Competencies

* **Digital Signal Processing (DSP):** IIR/FIR Digital Filter Design, Zero-Phase Filtering, Adaptive Filtering (LMS / NLMS), Spectral Estimation (Welch PSD), Compressive Sensing (OMP), Wavelet & Short-Time Fourier Transform (STFT).
* **Languages & Firmware:** Python (SciPy, NumPy, Scikit-Learn), ANSI C99 (Zero-Malloc, Embedded Systems), C++, MATLAB.
* **Domains & Standards:** Biomedical Telemetry (PhysioNet, MIT-BIH, AAMI EC57), RF & Wireless Channel State Information (CSI), Digital Hearing Aid Architectures (ANSI S3.22, NAL-R, WDRC).
* **Tools & Platforms:** Git, Linux, Streamlit, Matplotlib, LaTeX / Overleaf.

---

### 📂 Featured Research & Engineering Projects

#### 1. [Edge-ECG-Monitor](https://github.com/hnosrati0-source/edge-ecg-monitor)
*Real-Time Biomedical DSP and Edge AI Arrhythmia Detector evaluated on MIT-BIH PhysioNet.*
* Pan-Tompkins QRS peak detection, zero-phase notch/bandpass conditioning, and autonomic HRV spectral decomposition (Welch LF/HF ratio).
* 16.3 KB standalone ANSI C99 firmware header running at **0.12 ms/beat latency** on constrained dual-core hardware.

#### 2. [Edge-Hearing-Aid-DSP](https://github.com/hnosrati0-source/edge-hearing-aid-dsp)
*Real-Time Embedded Audio DSP & Speech Enhancement Pipeline.*
* Closed-loop adaptive feedback cancellation (64-tap NLMS), frequency-domain spectral subtraction, and NAL-R Wide Dynamic Range Compression (WDRC).
* Executes within an ultra-low acoustic latency budget of **0.8 ms per 128-sample frame** (<10 ms medical budget).

#### 3. [Contactless-Vital-RF-Sensing](https://github.com/hnosrati0-source/contactless-vital-rf-sensing)
*Non-Contact Respiration and Heart Rate Telemetry from 5.8 GHz RF Phase Shifts & Wi-Fi CSI.*
* Carrier frequency offset (CFO) regression and dual-band IIR decomposition isolating sub-millimeter cardiac chest wall vibrations (0.3 mm) without wearable sensors.
* Throughput: **>9,400× faster than real-time** (0.001 ms per packet).

#### 4. [IoT-Compressive-Sensing](https://github.com/hnosrati0-source/iot-compressive-sensing)
*Sub-Nyquist Biomedical Telemetry for Ultra-Low-Power Wearable IoT Nodes.*
* Asymmetric compressive sensing reducing wireless transmission volume by **50% to 70%**; OMP sparse recovery in DCT basis achieving clinical fidelity (**PRD = 0.24%**, SNR = 52.3 dB).

---

### 📫 Connect with Me
* **Email:** hnosrati0@gmail.com
* **GitHub:** [github.com/hnosrati0-source](https://github.com/hnosrati0-source)
