---
layout: page
title: Speech Emotion Recognition Using Machine Learning
description: Audio processing and Machine Learning classification on the RAVDESS dataset.
img: assets/img/immagine_emozioni.jpg
importance: 3
category: Machine Learning
---
**Tools:** Python, Scikit-learn, SVM, Random Forest, shapeDTW
*Context: Machine Learning & Audio Processing Project*

* Conducted a comparative analysis of classical Machine Learning classifiers (SVM vs. Random Forest) for Speech Emotion Recognition on the RAVDESS dataset.
* Extracted and analyzed static acoustic descriptors alongside dynamic temporal features (MFCC sequences), aligned using the shape Dynamic Time Warping (shapeDTW) algorithm.
* Ensured robust, unbiased model evaluation through a strictly gender-balanced, speaker-independent Nested Group K-Fold cross-validation protocol.
* **Result:** Built a Hybrid SVM classifier that successfully disentangles highly ambiguous, low-arousal emotional clusters, significantly outperforming the rigid decision boundaries of the Random Forest benchmark.

[📄 Read the full Paper](/assets/pdf/Speech_Emotion_Recognition.pdf)
