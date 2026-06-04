# 🛢️ UV Light Oil Leak Detection System

## 📌 Project Overview

The UV Light Oil Leak Detection System is an intelligent inspection solution designed to detect oil leaks in industrial equipment, pipelines, automotive engines, and machinery using ultraviolet (UV) fluorescence technology. The system identifies fluorescent oil traces under UV illumination and helps maintenance teams locate leaks quickly, reducing downtime, environmental hazards, and maintenance costs.

This project combines UV light-based inspection with image processing and automated detection techniques to improve the accuracy and speed of oil leak identification.

## 🎯 Objectives

- Detect oil leaks using UV fluorescence technology.
- Improve maintenance efficiency through early leak detection.
- Reduce equipment failure caused by unnoticed oil leakage.
- Minimize environmental pollution and safety risks.
- Provide a low-cost and portable inspection solution.

## 🚀 Features

- Real-time oil leak detection
- UV fluorescence-based inspection
- High detection accuracy
- Portable and easy-to-use design
- Automated image analysis
- Leak localization and highlighting
- Low maintenance cost
- Environment-friendly monitoring

## 🛠️ Technologies Used

### Hardware

- UV LED Light Source
- Camera Module
- Arduino Uno / ESP32
- Power Supply
- Protective UV Filter
- Industrial Test Surface

### Software

- Python
- OpenCV
- NumPy
- Arduino IDE
- VS Code

## ⚙️ Working Principle

1. Fluorescent dye is mixed with lubricating oil.
2. UV light illuminates the inspection area.
3. Oil traces fluoresce under UV exposure.
4. Camera captures the fluorescent regions.
5. Image processing algorithms identify leak patterns.
6. Detected leak locations are highlighted and reported.

## 🏗️ System Architecture

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

## 📂 Project Structure

```text
UV-Oil-Leak-Detection/
│
├── images/
├── dataset/
├── src/
├── docs/
├── results/
└── README.md
```

## 📊 Detection Methodology

### Image Acquisition

- Capture images under UV illumination.

### Preprocessing

- Noise reduction
- Contrast enhancement
- Color filtering

### Feature Extraction

- Fluorescence intensity analysis
- Region segmentation

### Leak Identification

- Threshold-based detection
- Contour extraction
- Leak localization

## 📈 Expected Results

- Accurate oil leak detection
- Faster inspection process
- Reduced maintenance costs
- Increased equipment reliability
- Early failure prevention

## 💡 Applications

### Automotive Industry

- Engine oil leak detection
- Transmission fluid inspection

### Manufacturing Plant
- Hydraulic system monitoring
- Machinery maintenance

<img width="537" height="342" alt="Screenshot 2026-02-02 143711" src="https://github.com/user-attachments/assets/71b67a95-c4d0-4902-98f8-060f2c5f0098" />

### Oil & Gas Industry

- Pipeline inspection
- Equipment monitoring

### Power Plants

- Turbine lubrication inspection

## 🔮 Future Enhancements

- AI-based leak classification
- Mobile application integration
- IoT-based remote monitoring
- Cloud dashboard analytics
- Real-time maintenance alerts
- Predictive maintenance using machine learning

## 📸 Sample Output

```text
Leak Detected!

Location:
X = 245
Y = 178

Confidence:
96.4%
```
<img width="1920" height="1080" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/fe0da56c-d90c-480a-8114-be7f5c82a49a" />


<img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/beadc277-bd9d-43de-a259-f2670e0e3aa4" />


## 📋 Advantages

- Non-destructive testing
- Fast inspection
- High accuracy
- Portable design
- Cost-effective
- Reduced downtime

## 👨‍💻 Developer

SANJAY KUMAR H
DEVASANJAY N

## 🏢 Internship

Developed during internship at Stellantis.

## 📄 License

MIT License

## ⭐ Support

If you find this project useful, please give it a star ⭐ and support future improvements.
