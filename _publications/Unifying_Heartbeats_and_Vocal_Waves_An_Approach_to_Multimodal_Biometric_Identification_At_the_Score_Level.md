---
title: "Unifying Heartbeats and Vocal Waves: An Approach to Multimodal Biometric Identification At the Score Level"
collection: publications
category: manuscripts
permalink: /publication/Unifying_Heartbeats_and_Vocal_Waves_An_Approach_to_Multimodal_Biometric_Identification_At_the_Score_Level
excerpt: 'ECG+voice multimodal biometrics using CNNs achieves 100% accuracy via score-level fusion, boosting security and robustness in identification.'
date: 2025-05-21
venue: 'Arabian Journal for Science and Engineering'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://rdcu.be/em4qV'
bibtexurl: #'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Zehir, H., Hafs, T., & Daas, S. (2025). Unifying Heartbeats and Vocal Waves: An Approach to Multimodal Biometric Identification At the Score Level. Arabian Journal for Science and Engineering, 1-20.'
---
Multimodal biometric systems have received substantial interest for their potential to improve identification accuracy and security in a variety of applications. In this paper, we propose a multimodal biometric system that combines electrocardiogram (ECG) and voice modalities for user identification. The ECG signals are processed using a 6th-order Butterworth filter and segmented around R peaks identified by the Pan-Tompkins++ approach. Instantaneous frequencies extracted using the Hilbert transform are utilized as features and fed into a 1D convolution neural network for classification. Similarly, voice signals are preprocessed by removing silent parts and segmented into 300 ms windows with 150 ms overlap. Mel-frequency cepstral coefficients (MFCCs) are extracted and input into a 2D convolution neural network for classification. Both individual modalities achieve high accuracies of 98.39% and 96.26%, respectively. Subsequently, a score-level fusion model, comprising densely connected layers, integrates the classification scores from both modalities, resulting in a remarkable 100% accuracy. The proposed multimodal biometric system demonstrates the efficacy of combining ECG and voice modalities for robust and accurate user identification. This research contributes to advancing multimodal biometric technologies and holds promise for applications requiring secure and reliable authentication systems.