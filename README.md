# 🛢️ Intelligent UV Fluorescence Oil Leak Detection System using Computer Vision

> **Developed during Internship at Stellantis (Citroën), Thiruvallur**

## 📖 Overview

The **UV Light Oil Leak Detection System** is an intelligent inspection solution that detects oil leaks in industrial equipment using **UV fluorescence technology** and **computer vision**. Fluorescent dye mixed with lubricating oil glows under ultraviolet light, allowing OpenCV-based image processing algorithms to identify and localize leaks accurately.

This project was developed to reduce inspection time, improve maintenance quality, minimize downtime, and provide a low-cost portable inspection solution.

---

# 🎯 Objectives

- Detect oil leaks using UV fluorescence
- Automate inspection using Computer Vision
- Reduce manual inspection time
- Improve maintenance efficiency
- Reduce equipment downtime
- Prevent environmental pollution
- Support predictive maintenance

---

# 🚀 Features

- Real-time leak detection
- UV fluorescence inspection
- Automatic image processing
- Leak localization
- High detection accuracy
- Portable hardware setup
- Low maintenance cost
- Environment-friendly monitoring

---

# 🛠 Technologies

## Hardware

- UV LED Light Source
- Camera Module
- Arduino UNO / ESP32
- UV Protective Filter
- Power Supply
- Industrial Test Surface

## Software

- Python
- OpenCV
- NumPy
- Arduino IDE
- VS Code

---

# ⚙ Working Principle

1. Mix fluorescent dye with lubricating oil.
2. Illuminate the surface using UV light.
3. Oil traces fluoresce brightly.
4. Capture images using a camera.
5. Process images using OpenCV.
6. Detect fluorescent regions.
7. Highlight leak location.
8. Generate inspection output.

---

# 🏗 System Architecture

```text
+----------------+
| UV Light Source|
+--------+-------+
         |
         v
+----------------+
| Oil Leak Area  |
+--------+-------+
         |
         v
+----------------+
| Camera Module  |
+--------+-------+
         |
         v
+----------------+
| Image Processing|
|    (OpenCV)    |
+--------+-------+
         |
         v
+----------------+
| Leak Detection |
+--------+-------+
         |
         v
+----------------+
| Alert / Report |
+----------------+
```

---

# 📂 Project Structure

```text
UV-Oil-Leak-Detection/
│
├── images/
├── dataset/
├── src/
├── docs/
├── results/
├── README.md
└── LICENSE
```

---

# 📊 Detection Methodology

## Image Acquisition
Capture images under UV illumination.

## Preprocessing
- Noise Reduction
- Contrast Enhancement
- Color Filtering

## Feature Extraction
- Fluorescence Analysis
- Region Segmentation

## Leak Identification
- Thresholding
- Contour Detection
- Leak Localization

---

# 📈 Expected Results

- Accurate oil leak detection
- Faster inspection
- Reduced downtime
- Early failure prevention
- Lower maintenance cost

---

# 📷 Project Images

## Manufacturing Plant

<img width="537" height="342" alt="Manufacturing Plant" src="https://github.com/user-attachments/assets/71b67a95-c4d0-4902-98f8-060f2c5f0098" />

---

## Sample Output 1

<img width="1920" height="1080" alt="Output1" src="https://github.com/user-attachments/assets/fe0da56c-d90c-480a-8114-be7f5c82a49a" />

---

## Sample Output 2

<img width="1920" height="1080" alt="Output2" src="https://github.com/user-attachments/assets/beadc277-bd9d-43de-a259-f2670e0e3aa4" />

---

# 💡 Applications

- Automotive Industry
- Manufacturing Plants
- Oil & Gas Industry
- Power Plants
- Heavy Machinery
- Aerospace
- Marine Industry

---

# 📋 Advantages

- Non-destructive testing
- High accuracy
- Cost-effective
- Portable
- Easy deployment
- Fast inspection

---

# 🔮 Future Enhancements

- AI-based leak classification
- YOLO integration
- Mobile app
- IoT monitoring
- Cloud dashboard
- Predictive maintenance

---

# 👨‍💻 Developers

- **Sanjay Kumar H**
- **Devasanjay N**

---

# 🏢 Internship

Developed during internship at **Stellantis (Citroën), Thiruvallur**.

---

# 📄 License

MIT License

---

# ⭐ Support

If you found this project useful, please give it a **Star ⭐**.
