# Nadi-Pariksha

🧘 Sensor-Based Nadi Pariksha Diagnostic Machine

A sensor-driven digital system for Ayurvedic Nadi Pariksha (pulse diagnosis) that objectively analyzes Vata, Pitta, and Kapha doshas using modern biomedical sensors, embedded systems, and signal-processing algorithms.

This project bridges traditional Ayurvedic diagnostics with digital health technologies, improving repeatability, scalability, and preventive healthcare integration.

📌 Project Overview

Nadi Pariksha is a core Ayurvedic diagnostic technique based on pulse examination. Traditional methods depend heavily on practitioner skill and are often subjective.

This project proposes a sensor-based pre-prototype system that:

Digitizes pulse examination

Measures pulse rate, rhythm, strength, and temperature

Maps physiological signals to dosha dominance

Displays results on a digital dashboard

🎯 Key Objectives

Reduce subjectivity in Ayurvedic pulse diagnosis

Digitize Vata–Pitta–Kapha pulse characteristics

Enable repeatable and objective analysis

Support preventive and integrative healthcare

Align with AYUSH & ABDM (India’s Digital Health Mission)

🧠 System Architecture
1️⃣ Sensor Layer

Pressure Sensors (Piezoelectric / Piezoresistive)

PPG Sensors (Photoplethysmography)

Skin Temperature Sensor (Tapamana)

Sensors are placed at classical Vata, Pitta, Kapha wrist positions.

2️⃣ Embedded System

Microcontroller (e.g., Arduino Nano)

ADC-based signal acquisition

Noise filtering (0.5–20 Hz bandpass)

Bluetooth / USB communication

3️⃣ Software & Analytics

Pulse waveform analysis

Feature extraction:

Heart Rate (Vega)

Rhythm (Tala)

Strength (Bala)

Shape/Tension (Akruti)

Temperature (Tapamana)

Rule-based & ML-ready dosha classification logic

📊 Dashboard (UI)

The system provides a digital dashboard that displays:

Live pulse waveforms (PPG & pressure)

Heart rate & variability

Temperature readings

Dosha dominance visualization (Vata / Pitta / Kapha)

🔗 Dashboard Link (Add Here)

👉 Live Dashboard / Demo:
(https://nadi-pariksha-ts.web.app/)

(Replace with your deployed web app / mobile app / prototype UI link)

🧪 Validation Strategy

Double-blind comparison with expert Ayurvedic practitioners

Statistical agreement analysis (e.g., Cohen’s Kappa)

Iterative refinement using expert feedback

Future scope for clinical trials

🇮🇳 National Policy Relevance

This project aligns with:

AYUSH Integration

Ayushman Bharat Digital Mission (ABDM)

Preventive & community healthcare initiatives

Digital transformation of traditional medicine

🚀 Future Scope

Hardware prototype development

Machine Learning–based dosha classification

Multi-modal sensing (ECG + PPG)

Cloud-based analytics & telemedicine support

Integration with Digital Health IDs

🛠️ Tech Stack (Proposed)

Hardware: Arduino Nano, PPG Sensor, Pressure Sensor, DS18B20

Software: Embedded C / Python / Signal Processing

UI: Web or Mobile Dashboard

Connectivity: Bluetooth / USB

Future: AI / Machine Learning models

📄 Research Foundation

This repository is based on an academic research work titled:

“Sensor-Based Nadi Pariksha Diagnostic Machine”
Focused on digitizing Ayurvedic pulse diagnostics using biomedical sensors and digital health technologies. 

Paper

👨‍🎓 Authors

Tejendra Singh – BCA 2nd Year, Sharda University, Agra

Nitin Sharma – BCA 2nd Year, Sharda University, Agra

📜 License

This project is intended for academic, research, and educational purposes.
(Add an open-source license if you plan public collaboration.)
