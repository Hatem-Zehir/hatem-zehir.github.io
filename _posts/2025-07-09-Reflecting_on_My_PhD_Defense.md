---
title: 'Reflecting on My PhD Defense: Hybrid Multimodal Biometrics'
date: 2025-07-09
permalink: /posts/2025/07/Reflecting_on_My_PhD_Defense
tags:
  - PhD Thesis Defense
  - Multimodal Biometrics
  - Deep Learning
---

On **09 July 2025**, I had the honor of defending my PhD thesis in Electronics, titled:
**“Development of a Hybrid Multimodal Biometric System.”**

![poster announcing my PhD defense](https://hatem-zehir.github.io/files/images/affichage_de_soutenance.jpg)  
*A proud moment: the official poster announcing my PhD defense.*

The work focused on advancing biometric authentication through the combination of two distinct modalities: ECG signals as a hidden physiological trait, and voice data as a behavioral trait. By fusing these heterogeneous signals, the system achieved higher accuracy, stronger robustness across variable conditions, and improved resilience against spoofing compared to traditional unimodal approaches.

For those interested, you can find the full thesis [here](https://dspace.univ-annaba.dz/items/928107ec-ec62-4d8e-9080-e4f926d2643d) and the defense presentation [here](https://hatem-zehir.github.io/files/thesis_presentation.pdf).

---

# Research Overview

The thesis centered on the design and evaluation of three complementary biometric systems:

## ECG-Based Identification System

ECG signals are highly distinctive and difficult to forge, making them a promising biometric modality. However, they are also sensitive to noise and recording artifacts, which necessitated careful preprocessing. To address this, I first applied a **4th-order Butterworth bandpass filter** (1–40 Hz) to denoise the raw signals while preserving the essential cardiac frequency components.

Next, I performed R-peak detection using the **Pan-Tompkins algorithm**, which provided reliable heartbeat localization across subjects. The ECG signals were then decomposed using **Empirical Mode Decomposition (EMD)**. From this decomposition, I retained only the first two Intrinsic Mode Functions (IMFs), which capture the most informative high-frequency content related to individual-specific cardiac morphology. Segmentation was then carried out: using the indexed R-peaks as anchors, I extracted fixed-length windows of the IMFs. This approach standardized the data while ensuring that each segment was physiologically meaningful.

To learn temporal dependencies within these segments, I employed **Gated Recurrent Unit (GRU)** and **Long Short-Term Memory (LSTM)** neural networks. This recurrent architecture allowed the system to model subtle rhythm variations between individuals. Despite using only the first two IMFs, the approach yielded robust identification results, validating ECG as a powerful physiological biometric.

## Voice-Based Identification System

Voice is an intuitive and widely accessible biometric trait, but one that is sensitive to noise and susceptible to spoofing. To strengthen its reliability, I applied a silence removal step to discard non-informative segments, followed by fixed-window segmentation to standardize the samples for feature extraction.

From each window, I extracted **Mel-Frequency Cepstral Coefficients (MFCCs)** along with their **first and second derivatives**, capturing both the static spectral shape and its dynamic evolution. These features were fed into a **Convolutional Neural Network (CNN)**, which excels at detecting local structures and invariant patterns in data. This approach allowed the system to generalize across different voice conditions while maintaining high discriminative power.

## Multimodal Fusion System

The most impactful contribution of my work was the integration of ECG and voice into a **hybrid multimodal framework**. Rather than combining raw features, I adopted a **score-level fusion** strategy, allowing each modality to be processed optimally before merging their decision outputs.

I employed both **Support Vector Machine (SVM) and Softmax** classifiers for decision-making, and explored multiple fusion strategies including the **sum, max, and product rules**. Across evaluations, the multimodal system consistently outperformed the unimodal baselines, demonstrating higher accuracy and resilience. Notably, the system also offered improved security against spoofing attacks: compromising both ECG and voice simultaneously is far more challenging than forging either modality in isolation.

---

# The Defense Experience

Defending my thesis was one of the most memorable moments of my academic journey. Standing before a distinguished committee, I presented the methodology, experimental results, and the broader implications of the research.

The defense was both rigorous and rewarding: each question pushed me to articulate not only the technical details but also the vision behind the work. It was a moment to reflect on years of research, challenges, and breakthroughs, translating countless hours of experimentation into a coherent narrative.

---

# Jury Members

I had the privilege of defending my work before an esteemed jury, whose expertise and feedback enriched the discussion:

Name and surname | University | Quality
| ----------- | ----------- | ----------- |
Prof. GHERBI Sofiane | Badji Mokhtar - Annaba University | President
Dr. HAFS Toufik | Badji Mokhtar - Annaba University | Supervisor
Dr. DAAS Sara | Badji Mokhtar - Annaba University | Co-supervisor
Dr. ZERMI Narima | Badji Mokhtar - Annaba University | Examiner
Prof. OUCHTATI Salim | 20 August 1955 University - Skikda | Examiner
Prof. BOUROUBA Hocine | 08 May 1945 University - Guelma | Examiner

I am deeply grateful for their thoughtful questions, constructive insights, and recognition of the work’s quality.

---

# Recognition

At the end of the defense, I was honored to receive the distinction:
**“Very Honorable, with Committee Praise.”**

This recognition reflects not only the technical contributions of the thesis but also the dedication and perseverance throughout the research process. It was a moment of pride and gratitude, to my supervisors, collaborators, family, and friends, whose support made the journey possible.

---

# Closing Thoughts

This defense marks the culmination of years of research and discovery, but also the beginning of new opportunities to apply and extend these ideas. Biometrics, deep learning, and AI continue to evolve rapidly, and I look forward to contributing further to these exciting fields.