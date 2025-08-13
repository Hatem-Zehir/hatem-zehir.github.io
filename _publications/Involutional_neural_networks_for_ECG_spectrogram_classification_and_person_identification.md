---
title: "Involutional neural networks for ECG spectrogram classification and person identification"
collection: publications
category: manuscripts
permalink: /publication/Involutional_neural_networks_for_ECG_spectrogram_classification_and_person_identification
excerpt: 'ECG spectrograms classified by INNs achieve up to 97.93% accuracy, outperforming CNNs by better capturing local and temporal heartbeat patterns.'
date: 2024-07-15
venue: 'International Journal of Signal and Imaging Systems Engineering'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: #'https://rdcu.be/em4qV'
bibtexurl: #'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Zehir, H., Hafs, T., & Daas, S. (2024). Involutional neural networks for ECG spectrogram classification and person identification. International Journal of Signal and Imaging Systems Engineering, 13(1), 41-53.'
---
Reliable personal identification is crucial. This study explores an ECG-based system using spectrograms and involutional neural networks (INNs) for accurate person identification. The system first preprocesses ECG signals with a Butterworth filter and segments them using the Pan-Tompkins++ algorithm. Each segment, representing a heartbeat, is then converted into a spectrogram using the short-time Fourier transform (STFT). Finally, an INN classifies the spectrograms for identification. Tested on the MIT-BIH Arrhythmia and Physikalisch-Technische Bundesanstalt (PTB) databases, the system achieved accuracies of 97.93% and 97.63%, respectively, surpassing conventional methods like convolutional neural networks (CNNs). This improvement is attributed to INNs' ability to better capture both local and temporal patterns in the spectrogram data.