---
permalink: /
title: "Hatem Zehir - Biometrics, Deep Learning and More"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, and welcome. My name is Hatem Zehir, and I hold a PhD in Electronics with a specialization in security and biometrics. My academic journey has been shaped by a deep curiosity about how technology can reliably recognize and protect individuals. From the very beginning of my studies, I was fascinated by the idea that something as unique as a heartbeat could serve as a secure key to identity.

# What I Work On
My research centers on the development of biometric authentication systems that combine the strengths of signal processing, deep learning, and artificial intelligence. I am particularly interested in how these disciplines can be integrated to address the limitations of conventional systems, and to design solutions that are both scientifically rigorous and practically applicable.

A major focus of my doctoral work was the design of a hybrid multimodal biometric system that fuses ECG signals and voice data at the score level. The rationale behind this choice lies in the complementary nature of the two modalities: ECG provides a physiological trait that is internal, difficult to replicate, and inherently secure, while voice offers a behavioral trait that is natural, user-friendly, and widely accessible. By combining them, I aimed to improve the accuracy, robustness, and resilience to spoofing that cannot be achieved by unimodal systems alone.

On the ECG side, I explored advanced signal processing techniques such as empirical mode decomposition (EMD), and applied deep learning models including GRU and LSTM architectures. These methods enabled the extraction of meaningful features from highly complex and variable biometric signals, and their integration into a reliable decision-making framework.

On the voice side, I designed a system based on Mel-Frequency Cepstral Coefficients (MFCCs), along with their first and second derivatives, to capture both the spectral envelope and the dynamic changes of speech. MFCCs have long been established as a robust representation of human auditory perception, making them particularly well-suited for voice-based biometrics. To model these features, I employed a convolutional neural network (CNN), which excels at identifying spatial correlations in the spectral domain. This pairing of MFCC-based features with CNN classification allowed the system to effectively capture speaker-specific traits, while remaining resilient to variability in recording conditions.

The integration of ECG and voice was performed at the score level, where I implemented several fusion strategies to combine the outputs of the unimodal classifiers. Specifically, I used support vector machines (SVMs) and Softmax-based normalization to align and standardize the scores, followed by different decision rules such as the sum rule, max rule, and product rule. These methods provided a structured way of evaluating how best to aggregate evidence from the two modalities. Through systematic experimentation, I was able to demonstrate that multimodal fusion consistently outperformed unimodal systems, delivering higher recognition accuracy and enhanced resilience to spoofing attempts.

Beyond multimodal fusion, I also investigate unimodal systems based on ECG alone, studying their potential as a secure standalone modality. In parallel, I maintain an active interest in image processing and computer vision, as I believe these fields will play an increasingly important role in the future of multimodal AI systems.

At the core of my work lies a strong interest in deep learning and machine learning methodologies. What fascinates me most is their ability to uncover patterns that are often invisible to the human eye or too complex for traditional approaches to capture. When I work with biometric signals, speech, or images, I find it remarkable how these models can transform raw, noisy data into meaningful representations that reflect something as personal and unique as human identity. For me, deep learning is not just a tool; it is a way of bridging theory with real-world applications, and of turning data into insight.

Arthur C. Clarke once wrote that *“Any sufficiently advanced technology is indistinguishable from magic.”* To me, deep learning often feels like that kind of magic, a way of coaxing intelligence out of complexity, and of finding structure and meaning in places where we once saw only noise. This sense of discovery is what keeps me motivated to keep exploring and pushing the boundaries of what these systems can achieve.

While deep learning forms the backbone of my investigations, I also retain a strong interest in signal processing and image analysis. These areas provide the essential tools for preparing, enhancing, and interpreting raw data, and I view them as indispensable complements to machine learning methods. For me, combining the strengths of classical processing techniques with modern AI approaches opens new avenues for robust and reliable system design.

My research has been disseminated through several first-authored publications in international journals, which are detailed in the [Publications section](https://hatem-zehir.github.io/publications/) of this website.

# Why I Do This Work
My interest in artificial intelligence began with a simple question that has stayed with me ever since: can machines learn to see the world as we do, or even in ways we cannot? That question first emerged from curiosity, a fascination with the way humans can recognize patterns almost instinctively, while computers require explicit instructions. I wondered what might happen if machines could go beyond rules and instead learn on their own. This curiosity soon grew into a passion: the more I studied AI, the more I saw its potential to reshape not only technology, but the way we understand ourselves.

For me, the most exciting aspect of AI lies in its ability to reveal the invisible. Deep learning models can take raw signals, fragments of voice, or pixels from an image and transform them into meaningful representations that reflect something profoundly human. In these moments, AI feels less like a cold, mechanical tool and more like a companion in discovery, one that allows us to see what we could not see before.

Over time, this fascination led me toward the study of identity. Few questions are as fundamental as what makes us unique, and how can we prove that uniqueness? Biometrics gave me a way to explore this question scientifically. By working with ECG signals, voice, and other modalities, I found a field where AI could be applied not just to abstract datasets, but to something deeply human. The systems I build are not only about improving accuracy or robustness; they are also about protecting individuality, ensuring security, and designing technologies that recognize people for who they truly are.

At the heart of it all is a belief that research is a journey of discovery rather than a race to a finish line. Each experiment, each new model, carries the possibility of an insight that reshapes the way I think. Even setbacks, a model that fails to converge, or an unexpected variation in biometric data, are moments of learning that deepen my understanding. In this sense, AI research mirrors life itself: full of challenges, surprises, and opportunities to see the familiar in a completely new way.

When I was young, I spent my summers exploring Koholint Island in The Legend of Zelda: Link’s Awakening (or Île Cocolint, as I played it in French). That game left a deep mark on me, not only because of its mystery and adventure, but because it taught me that even the smallest worlds are full of hidden secrets waiting to be uncovered. Today, I feel much the same way when working in AI: every dataset is its own island, and every algorithm a tool for discovery.

I also grew up with Pokémon Blue, and later with Gold and Silver. In Gen 1, the thrill came from simply discovering and capturing new creatures, much like my early encounters with AI, where everything felt new, uncharted, and full of possibility. Then came Gen 2, with its richer mechanics, evolving systems, and the surprising return to the original Kanto region. That deeper complexity mirrors the way research unfolds: the more you learn, the more layers you uncover, and the more connections you see between what seemed like separate worlds. For me, AI carries that same evolving sense of wonder, it starts with curiosity, but it grows into a lifelong journey where each discovery opens the door to another.

# Vision & Future Directions

As I look ahead, my focus is on advancing research in deep learning, signal processing, and image processing, fields that lie at the heart of today’s AI revolution. These areas provide the tools to uncover structure in complex data, turning signals, images, and multimodal information into insights that can power real applications. My doctoral research applied these methods to biometric authentication, but their potential extends far beyond, reaching into healthcare, computer vision, and intelligent data-driven systems.

I am especially motivated by the challenge of making AI systems that are not only accurate but also robust, adaptable, and trustworthy. Real-world data is messy, it contains noise, variation, and uncertainty — and part of my vision is to design models that can thrive under those conditions. Whether working with signals from the human body or patterns in images, I see deep learning as a framework that can bring clarity and reliability to complex problems.

In the next phase of my career, I am seeking opportunities as a **postdoctoral researcher** or in academic positions such as **Lecturer** or **Assistant Professor**, where I can expand this research while also contributing to teaching and mentoring. I believe strongly in the value of helping students and early researchers navigate the exciting but challenging world of AI, building skills that combine theory with practice. At the same time, I remain open to collaborations with industry, where applied research can directly shape technologies used in everyday life.

My long-term vision is to contribute to a research community where deep learning, guided by signal and image processing, drives new discoveries. As Carl Sagan once wrote: *“Somewhere, something incredible is waiting to be known.”* That sense of curiosity and exploration continues to guide my work, and it is the same spirit I hope to bring to future research, teaching, and collaborations.
