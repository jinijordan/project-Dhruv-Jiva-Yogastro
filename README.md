# 🌌 Project Dhruv 
> **Harmonizing Astronaut Health in Deep Space Through Biometric Monitoring & Yoga Physiology**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![NASA Space Apps Challenge 2026](https://img.shields.io/badge/NASA%20Space%20Apps-2026-blue.svg)](https://www.spaceappschallenge.org/)
[![Team](https://img.shields.io/badge/Team-Jiva%20Yogastro-orange.svg)](#team-jiva-yogastro)

---

## 📌 Executive Summary

**Project Dhruv** is an adaptive, data-driven health and mental well-being monitoring system designed for astronauts in isolated, confined, and extreme (ICE) spaceflight environments.

Named after the North Star (*Dhruv*)—symbolizing unshakeable stability and orientation—our system continuously integrates real-time physiological biometrics (ECG, HRV, GSR) and neurological indicators (EEG spectral band power) to compute a composite **Spaceflight Stress & Balance Index**.

By marrying open NASA physiological datasets with ancient, scientifically proven yoga practices (*Asana*, *Pranayama*, and *Yoga Nidra*), Dhruv dynamically prescribes personalized physical and psychological micro-interventions to counteract microgravity deconditioning, fluid shift stress, autonomic dysregulation, and cognitive fatigue.

---

## 🚀 Key Features

* **🧠 Multi-Modal Biometric & Neurological Monitoring:** Real-time analysis of Heart Rate Variability (RMSSD, LF/HF ratios) and EEG brainwave dynamics ($\alpha/\beta$ and $\theta/\beta$ ratios).
* **📊 Composite Stress & Balance Index Algorithm:** A Python-driven analytics engine that maps physiological distress and vagal nerve tone into actionable health scores.
* **🧘 Adaptive Yoga Intervention Engine:** Recommends targeted isometric postures, controlled breathing (*Pranayama*), and guided relaxation (*Yoga Nidra*) based on current stress levels.
* **📉 Brainwave Synchronization Feedback Loop:** Visualizes the transition from high-stress Beta wave activity ($13\text{--}30\text{ Hz}$) to relaxed Alpha/Theta states ($4\text{--}12\text{ Hz}$) during guided sessions.
* **🪐 Mission Phase Optimization:** Custom protocols tailored for **Pre-Flight Conditioning**, **In-Flight Microgravity Adaptation**, and **Post-Flight Recovery**.

---

## 🔬 Scientific Basis & NASA Open Data Sources

Project Dhruv is built upon peer-reviewed space physiology research and open datasets provided by NASA and open-access biomedical repositories:

1. **[NASA Life Sciences Data Archive (LSDA)](https://lsda.jsc.nasa.gov/):** Baseline physiological markers of muscle atrophy, bone density changes, and cardiovascular fluid shift adaptation in microgravity.
2. **[NASA OpenScience Data Repository (OSDR) / GeneLab](https://osdr.nasa.gov/):** Biomarkers and systemic stress responses observed in bed-rest analogue studies.
3. **[PhysioNet MIT-BIH & Sleep Databases](https://physionet.org/):** Multi-parameter electrocardiogram (ECG) and heart rate variability (HRV) metrics under psychological stress.
4. **OpenBCI / Muse EEG Datasets:** Brainwave spectral density shifts during mindfulness, deep relaxation, and high-cognitive load environments.

---

## 🛠 System Architecture
[ Astronaut Wearables ]
                     (ECG / HRV / EEG / GSR Sensors)
                                    │
                                    ▼
                     [ Dhruv Analytics Engine ]
              (Stress Index & Vagal Tone Algorithms)
                                    │
                ┌───────────────────┴───────────────────┐
                ▼                                       ▼
    [ Cardiovascular / Musculoskeletal ]      [ Neurological & Cognitive ]
    - Fluid Shift Monitoring                   - Brainwave Spectral Power
    - Postural Muscle Degradation              - Autonomic Stress Index
                │                                       │
                └───────────────────┬───────────────────┘
                                    ▼
                     [ Adaptive Intervention Engine ]
              - Targeted Isometric Asanas & Pranayama
              - Real-Time EEG Relaxation Visualizer

---

## 🗂 Project Structure

```bash
Project-Dhruv-Jiva-Yogastro/
├── docs/                      # Pitch deck, presentation assets, and diagrams
├── data/                      # Sample/processed NASA LSDA & PhysioNet datasets
├── analytics/                 # Python scripts for HRV and EEG feature extraction
│   └── stress_engine.py       # Core Stress Index calculation script
├── dashboard/                 # Streamlit / React UI source code for astronaut portal
├── LICENSE                    # MIT Open Source License
└── README.md                  # Project documentation


⚡ Quick Start & Installation
Prerequisites
Python 3.9+
Git
git clone [https://github.com/jinijordan/project-Dhruv-Jiva-Yogastro.git](https://github.com/jinijordan/project-Dhruv-Jiva-Yogastro.git)
cd project-Dhruv-Jiva-Yogastro
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
streamlit run dashboard/app.py




📄 License
Distributed under the MIT License. See LICENSE for more information.

👥 Team Jiva Yogastro
Team Lead / System Architect: Jiya

Local Event: Mysuru, Karnataka, India

Challenge: NASA International Space Apps Challenge 2026

              
