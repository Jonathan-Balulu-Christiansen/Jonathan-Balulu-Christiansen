# Jonathan Balulu Christiansen

**Electrical and Electronics Engineer · Digital Signal Processing · Electro-Optics**

I work primarily in Python on signal processing, estimation, deep learning and computer vision projects. I enjoy developing the full workflow: preparing data, testing technical choices, evaluating results and building software for real-time use.

## Projects

### Real-Time Sound Classification Using Spectrograms and Deep Neural Networks

_Team project · source code not public_

Designed and developed an end-to-end, real-time sound event classification system, including acoustic drone detection, built around an AudioSet-pretrained dynamic CNN. The system converts live audio into log-Mel spectrograms to classify 13 sound categories, with dedicated tools for dataset curation, source tracking, and audio inspection.

**Python · PyTorch · CUDA · CNN · Transfer Learning · Audio DSP · Real-Time Inference · Raspberry Pi**

---

### [Radar Target Tracking with an Extended Kalman Filter](https://github.com/Jonathan-Balulu-Christiansen/EKF_Simulation)

Built a radar tracking simulator from the physics up: a 3-DOF model flies a generic ballistic vehicle through the standard atmosphere, a simulated X-band radar measures range, angles and Doppler, and a 10-state Extended Kalman Filter tracks the flight and estimates its ballistic coefficient. Noise levels are derived rather than tuned, consistency is verified with Monte Carlo NEES/NIS tests, and a live 3D desktop app shows every equation with its numbers.

**Python · NumPy · SciPy · Kalman Filtering · Radar Signal Processing · Monte Carlo · PySide6 · OpenGL**

<a href="https://github.com/Jonathan-Balulu-Christiansen/EKF_Simulation"><img src="assets/ekf-flight-3d.gif" alt="One full simulated flight in 3D, with the radar beam following the track over the atmosphere layers" width="100%"></a>

<sub>One full flight played at ×20. The target uses generic, illustrative values.</sub>

---

### [Real-Time License Plate Recognition](https://github.com/Jonathan-Balulu-Christiansen/LicensePlateRecognition)

Built a real-time system that detects, tracks and reads Israeli license plates from live cameras and video. A fine-tuned YOLO26m detector and ByteTrack locate and follow each plate, and a CNN+CTC network reads the full number in one pass, with readings voted across frames.

**Python · PyTorch · Keras · YOLO · OpenCV · PySide6 · Computer Vision**

<a href="https://github.com/Jonathan-Balulu-Christiansen/LicensePlateRecognition"><img src="assets/license-plate-recognition-live.png" alt="The license plate recognition app reading four plates at once in real time on a synthetic street scene" width="100%"></a>

<sub>The app running in real time on a synthetic scene. All plate numbers shown are fictional.</sub>

## Contact

[LinkedIn](https://www.linkedin.com/in/jonathan-balulu-christiansen/)
