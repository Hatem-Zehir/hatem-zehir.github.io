---
title: "ECG-Based Biometric System using TinyML: Implementation and Performance Evaluation on ESP32"
collection: publications
category: conferences
permalink: /publication/ECG_Based_Biometric_System_using_TinyML_Implementation_and_Performance_Evaluation_on_ESP32
excerpt: 'TinyML-based ECG biometric system on ESP32 achieves 96.71% accuracy, enabling resource-efficient personal identification.'
date: 2024-10-25
venue: 'ICAECCT23: The 1st International Conference on Advances in Electronics, Control and Computer Technologies'
slidesurl: 'https://hatem-zehir.github.io/files/conferences/Presentation_ECG_Based_Biometric_System_using_TinyML_Implementation_and_Performance_Evaluation_on_ESP32.pdf'
paperurl: 'https://hatem-zehir.github.io/files/conferences/ECG_Based_Biometric_System_using_TinyML_Implementation_and_Performance_Evaluation_on_ESP32.pdf'
citation: 'Zehir, H., Hafs, T., & Daas, S. ECG-Based Biometric System using TinyML: Implementation and Performance Evaluation on ESP32.'
---
This paper presents a novel biometric system based on electrocardiogram (ECG) signals and tiny machine learning (TinyML) techniques for personal identification. A subset of 10 individuals from the MIT-BIH Arrhythmia Database was used to develop and evaluate the proposed system. In the preprocessing stage, the ECG signals were denoised using a 4th-order Butterworth bandpass filter. Subsequently, the signals were segmented into 100ms windows centred around each r-peak, which were detected using the Pan-Tompkins++ algorithm. To ensure uniformity, the amplitudes of the segmented windows were normalized within the range of 0 to 1. For the classification, a deep learning model consisting of an input layer and three fully connected layers was employed. To enable deployment on resource-constrained devices, the trained model was converted to TensorFlow Lite format and further transformed into an Arduino library. The implemented system was successfully deployed on an ESP32 microcontroller, thereby demonstrating the feasibility of real-time biometric authentication using TinyML. The identification accuracy achieved was 96.71%.