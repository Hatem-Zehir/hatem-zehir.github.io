---
permalink: /
title: "Hatem Zehir - Biometrics, Deep Learning and More"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me
Hello, and welcome. My name is Hatem Zehir, and I hold a PhD in Electronics with a specialization in security and biometrics. My academic journey has been shaped by a deep curiosity about how technology can reliably recognize and protect individuals. From the very beginning of my studies, I was fascinated by the idea that something as unique as a heartbeat could serve as a secure key to identity.

During my doctoral research, I developed a hybrid multimodal biometric system that combines electrocardiogram (ECG) signals with voice data. This fusion of physiological and behavioral traits allowed me to explore novel methods of authentication that are more accurate, robust, and resilient to spoofing than traditional unimodal approaches.


Alongside biometrics, I maintain a strong interest in signal processing, image processing, deep learning, and artificial intelligence. What motivates me is the challenge of transforming complex data into meaningful patterns, and designing systems that remain reliable under diverse and unpredictable conditions. For me, research is not only about solving technical problems but also about contributing to a safer, more trustworthy interaction between humans and technology.

# What I Work On
My research centers on the development of biometric authentication systems that combine the strengths of signal processing, deep learning, and artificial intelligence. I am particularly interested in how these disciplines can be integrated to address the limitations of conventional systems, and to design solutions that are both scientifically rigorous and practically applicable.

A major focus of my doctoral work was the design of a hybrid multimodal biometric system that fuses ECG signals and voice data at the score level. The rationale behind this choice lies in the complementary nature of the two modalities: ECG provides a physiological trait that is internal, difficult to replicate, and inherently secure, while voice offers a behavioral trait that is natural, user-friendly, and widely accessible. By combining them, I aimed to improve the accuracy, robustness, and resilience to spoofing that cannot be achieved by unimodal systems alone.

On the ECG side, I explored advanced signal processing techniques such as empirical mode decomposition (EMD), and applied deep learning models including GRU and LSTM architectures. These methods enabled the extraction of meaningful features from highly complex and variable biometric signals, and their integration into a reliable decision-making framework.

On the voice side, I designed a system based on Mel-Frequency Cepstral Coefficients (MFCCs), along with their first and second derivatives, to capture both the spectral envelope and the dynamic changes of speech. MFCCs have long been established as a robust representation of human auditory perception, making them particularly well-suited for voice-based biometrics. To model these features, I employed a convolutional neural network (CNN), which excels at identifying spatial correlations in the spectral domain. This pairing of MFCC-based features with CNN classification allowed the system to effectively capture speaker-specific traits, while remaining resilient to variability in recording conditions.

The integration of ECG and voice was performed at the score level, where I implemented several fusion strategies to combine the outputs of the unimodal classifiers. Specifically, I used support vector machines (SVMs) and Softmax-based normalization to align and standardize the scores, followed by different decision rules such as the sum rule, max rule, and product rule. These methods provided a structured way of evaluating how best to aggregate evidence from the two modalities. Through systematic experimentation, I was able to demonstrate that multimodal fusion consistently outperformed unimodal systems, delivering higher recognition accuracy and enhanced resilience to spoofing attempts.

Beyond multimodal fusion, I also investigate unimodal systems based on ECG alone, studying their potential as a secure standalone modality. In parallel, I maintain an active interest in image processing and computer vision, as I believe these fields will play an increasingly important role in the future of multimodal AI systems.

At the core of my work lies a strong interest in deep learning and machine learning methodologies. What fascinates me most is their ability to uncover patterns that are often invisible to the human eye or too complex for traditional approaches to capture. When I work with biometric signals, speech, or images, I find it remarkable how these models can transform raw, noisy data into meaningful representations that reflect something as personal and unique as human identity. For me, deep learning is not just a tool; it is a way of bridging theory with real-world applications, and of turning data into insight.

Arthur C. Clarke once wrote that ** “Any sufficiently advanced technology is indistinguishable from magic.” ** To me, deep learning often feels like that kind of magic, a way of coaxing intelligence out of complexity, and of finding structure and meaning in places where we once saw only noise. This sense of discovery is what keeps me motivated to keep exploring and pushing the boundaries of what these systems can achieve.

While deep learning forms the backbone of my investigations, I also retain a strong interest in signal processing and image analysis. These areas provide the essential tools for preparing, enhancing, and interpreting raw data, and I view them as indispensable complements to machine learning methods. For me, combining the strengths of classical processing techniques with modern AI approaches opens new avenues for robust and reliable system design.

My research has been disseminated through several first-authored publications in international journals, which are detailed in the [Publications section](https://hatem-zehir.github.io/publications/) of this website.
