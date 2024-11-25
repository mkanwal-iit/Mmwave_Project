# mmWave Radar & Machine Vision Fusion for Pedestrian Collision Warning

## Abstract

This project demonstrates a fusion system combining **mmWave radar** and **machine vision** to enhance pedestrian collision warning in autonomous vehicles. By integrating radar depth profiling and machine learning-powered image classification, the system achieves robust obstacle detection in real-time.

---

## System Overview

### Components

- **Hardware**:
  - TI AWR1642BOOST mmWave Radar Sensor
  - NVIDIA Jetson Nano (single-board computer)
  - USB Camera
- **Software**:
  - OpenCV for image processing
  - numpy
  - time
  - mmw
  - humanClassify
  - TI mmWave SDK for radar data processing

### How It Works

1. The camera captures live video streams and sends them to the machine vision system for pedestrian detection.
2. The mmWave radar provides depth and velocity data for surrounding objects.
3. A fusion algorithm combines radar and vision data to improve detection accuracy and reliability.
4. Detected pedestrians and obstacles are visualized in real-time, warning the driver.

---

## Results

- **Improved Detection**: Achieved a 95% pedestrian detection accuracy by combining radar and vision systems.
- **Reduced Missed Detections**: Fusion reduced missed detections by 30% compared to vision-only systems.
- **Real-Time Processing**: Capable of detecting and displaying results in under 100ms.

---

## Screenshots

### System Diagram

![System Diagram](images/system_diagram.png)

### Radar Data Output

![Radar Output](images/radar_output.png)

### Pedestrian Detection

![Pedestrian Detection](images/pedestrian_detection.png)

---

## Report

For a detailed explanation of the project, including setup, methodology, and outputs, refer to the [Final Report (PDF)](FINAL_REPORT.pdf).

---

## Citation

If you use this work, please cite:

> M. Kanwal, "Design Flow of mmWave Radar and Machine Vision Fusion for Pedestrian Collision Warning," IEEE International Conference on Electro/Information Technology, 2022.