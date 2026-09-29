---
layout: page
title: Non-Contact Respiratory Rate Estimation
description: Appearance-invariant computer vision framework for pediatric pneumonia screening in low-resource settings
img: assets/img/12.jpg
importance: 1
category: research
related_publications: false
---

### Non-Contact, Appearance-Invariant Computer Vision for Point-of-Care Respiratory Rate Estimation

Continuous physiological monitoring of pediatric patients in low-resource triage and clinical settings is frequently constrained by a lack of specialized contact sensors, high equipment costs, and infant distress caused by physical attachment.

This research formulates an **appearance-invariant computer vision and video signal processing pipeline** designed for real-time respiratory rate (RR) estimation from standard RGB video feeds. Rather than relying on appearance-dependent deep learning models or ambient-light-sensitive color absorption (rPPG), the framework extracts subtle thoracic and chest-wall motion directly from optical video.

---

### Key Methodological Components

- **Thoracic Region Localization:** Dynamic bounding and tracking of thoracic and abdominal regions of interest across video frames.
- **Optical Motion Tracking:** Dense and sparse sub-pixel optical flow formulations to isolate subtle chest excursions from background noise and subject movements.
- **Signal Conditioning & Noise Filtration:** Temporal bandpass filtering and illumination normalization to decouple true respiratory kinematics from lighting flicker.
- **Spectral Frequency Decomposition:** Peak detection and spectral density analysis to extract dominant frequency peaks and map them to real-time breaths-per-minute (BPM).

---

### Research Details

| Detail | Description |
| :--- | :--- |
| **Degree** | Master of Philosophy (MPhil) in Biomedical Data Science |
| **Institution** | National Institute for Mathematical Sciences (NIMS), KNUST |
| **Supervisors** | Prof. Isaac K. Dontwi, Prof. Peter Amoako Yirenkyi & Dr. Rhydal Esi Eghan |
| **Core Tools** | Python, OpenCV, SciPy, NumPy, Matplotlib |
| **Primary Domain** | Computer Vision, Biomedical Signal Processing, Point-of-Care Digital Health |
