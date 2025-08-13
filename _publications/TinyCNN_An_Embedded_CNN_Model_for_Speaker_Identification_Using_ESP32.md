---
title: "TinyCNN: An Embedded CNN Model for Speaker Identification Using ESP32"
collection: publications
category: conferences
permalink: /publication/TinyCNN_An_Embedded_CNN_Model_for_Speaker_Identification_Using_ESP32
excerpt: 'Optimized quantized CNN for speaker recognition on ESP32 hits 98.58% accuracy, 53% faster and 73% smaller, enabling efficient edge deployment.'
date: 2025-11-22
venue: 'The 1st International Conference on Electrical Engineering & Renewable Energies Systems'
slidesurl: 'https://hatem-zehir.github.io/files/conferences/Presentation_TinyCNN_An_Embedded_Voice_Based_User_Identification_Using_ESP32.pdf'
paperurl: 'https://hatem-zehir.github.io/files/conferences/TinyCNN_An_Embedded_Voice_Based_User_Identification_Using_ESP32.pdf'
citation: 'Zehir, H., Hafs, T., & Daas, S. TinyCNN: An Embedded CNN Model for Speaker Identification Using ESP32.'
---
This research paper introduces a novel Convolutional Neural Network (CNN) architecture optimized for speaker recognition on resource-constrained devices. The proposed model was evaluated on a subset of 10 speakers from the LibriSpeech database. To process the audio signals, preprocessing techniques to remove silent parts and segmented the signals into 1-second windows with a 500 ms overlap were employed. The Mel Frequency Cepstral Coefficients (MFCC) of each window were then extracted and fed into the CNN model. After training, the CNN model was quantized, converted to TensorFlow Lite (TFLite) format, and integrated into an Arduino-compatible library. This deployment was successfully executed on the ESP32 board. The proposed quantized model achieved an impressive accuracy of 98.58%, outperforming the original model by being 53% faster and 73% smaller in size. The findings of this study prove the efficiency of deploying accurate and fast speaker recognition systems on edge devices.