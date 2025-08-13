---
title: "Empirical mode decomposition-based biometric identification using GRU and LSTM deep neural networks on ECG signals"
collection: publications
category: manuscripts
permalink: /publication/Empirical_mode_decomposition_based_biometric_identification_using_GRU_and_LSTM_deep_neural_networks_on_ECG_signals
excerpt: 'ECG biometrics using EMD with GRU/LSTM models achieves up to 99.17% accuracy across three databases, showing strong potential for secure identification.'
date: 2024-08-22
venue: 'Evolving Systems'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://rdcu.be/dRJ0H'
bibtexurl: #'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Zehir, H., Hafs, T., & Daas, S. (2024). Empirical mode decomposition-based biometric identification using GRU and LSTM deep neural networks on ECG signals. Evolving Systems, 15(6), 2193-2209.'
---
Traditional methods of authentication, such as keys, passwords, and PIN codes, are increasingly being surpassed by the robustness and security offered by biometric systems. This study presents a system for human identification using electrocardiogram (ECG) signals, evaluated using two deep learning models: gated recurrent units (GRU) and long short-term memory (LSTM). The proposed methodology begins with signal denoising using a bandpass filter, followed by the decomposition of the signal into multiple intrinsic mode functions (IMFs) via a signal processing technique, empirical mode decomposition (EMD). The first two IMFs, after normalization and segmentation, serve as features for the deep learning models. The performance of these models was assessed on three distinct databases: NSRDB, MIT-BIH, and PTB. MIT-BIH contains a mixture of healthy and ill subjects, while the PTB and NSRDB databases contain only healthy subjects. The GRU model achieved accuracies of 98.57%, 98.26%, and 99.17% on these databases respectively, while the LSTM model achieved accuracies of 98.33%, 97.89%, and 98.27% respectively, demonstrating its reliability for biometric applications. While the proposed system was tested only on ECG, its applications can be extended to include other biomedical signals, indicating its potential for broader biometric use.