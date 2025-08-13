---
title: "Hardware-Optimised CNN Architecture for ECG Biometric Identification on Embedded Systems"
collection: publications
category: manuscripts
permalink: /publication/Hardware_Optimised_CNN_Architecture_for_ECG_Biometric_Identification_on_Embedded_Systems
excerpt: 'Optimized quantized CNN for ECG biometrics hits 97.9% accuracy, 77% faster and 64% smaller, enabling efficient ESP32-based identification.'
date: 2025-01-01
venue: 'International Journal of Signal and Imaging Systems Engineering'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: #'[http://academicpages.github.io/files/paper1.pdf](https://link.springer.com/epdf/10.1007/s11042-025-21044-1)'
bibtexurl: #'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Zehir, H., Hafs, T., & Daas, S. (2025). Hardware-Optimised CNN Architecture for ECG Biometric Identification on Embedded Systems. International Journal of Signal and Imaging Systems Engineering'
---
This paper presents an optimized Convolutional Neural Network (CNN) for Electrocardiogram (ECG) biometrics, focusing on enhancing efficiency and performance using a quantized CNN model. The research evaluated the model on 10 subjects from the MIT-BIH database. ECG signals were filtered with a 4th-order Butterworth filter (1-40 Hz), and R-peaks were detected using the Pan-Tompkins++ algorithm. Segments around these peaks were windowed into 125 ms frames, and spectrograms were generated via short-time Fourier transform (STFT). These normalized spectrograms were fed into both standard and 8-bit quantized CNN models for biometric identification. The 8-bit quantized model, deployed on an ESP32, achieved 97.90% accuracy, outperforming the original model. It was 77% faster and 64% smaller in size, demonstrating significant improvements in efficiency and performance. The study suggests further exploration of quantized models in ECG biometrics.