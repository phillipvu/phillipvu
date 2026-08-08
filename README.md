# Phillip Vu

**Signal processing & navigation systems engineer** — radar, GNSS, sensor fusion, and real-time DSP, with a focus on taking estimation algorithms from prototype to GPU-accelerated, real-time implementations.

PhD in radar/estimation · IEEE Senior Member · Thousand Oaks, CA

---

### What I do

I build the hard parts of perception and navigation systems — the estimation math that turns noisy sensor data into a reliable state, and the high-performance code that runs it in real time on constrained hardware.

### Focus areas

- **Navigation & estimation** — GNSS receivers, GNSS-denied positioning, inertial navigation, Kalman/EKF tracking, multi-sensor (radar/lidar/camera) fusion
- **Radar & RF signal processing** — detection & estimation, phased arrays, micro-Doppler, phase noise, RF device identification
- **ML for sensors** — CNNs on signal data, Bayesian learning for RF observations, classification under noise
- **High-performance implementation** — CUDA acceleration of signal-processing kernels, real-time DSP on edge/embedded hardware

### Selected repositories

- **[cuda-gps-acquisition](https://github.com/phillipvu/cuda-gps-acquisition)** — GPU-accelerated GPS L1 C/A acquisition: parallel code-phase search with cuFFT, ~30× over a batched NumPy baseline, validated against a known-answer synthetic capture
- **[radar_matlab](https://github.com/phillipvu/radar_matlab)** — radar detection and phase-noise modeling in MATLAB
- **[Learning_Identification_Internode_Dynamics](https://github.com/phillipvu/Learning_Identification_Internode_Dynamics)** — Bayesian (HSMM) learning framework for characterizing wireless RF observations and classifying RF devices as distinct states
- **[data_science_for_wireless_network](https://github.com/phillipvu/data_science_for_wireless_network)** — data-science methodology for wireless-networks research

### Currently

Building GPU-accelerated GNSS and radar signal-processing kernels — bridging MATLAB/Python prototypes to real-time CUDA/C++ implementations.
