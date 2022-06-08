---
layout: post
title: Probably Pleasant? A Neural-Probabilistic Approach to Automatic Masker Selection for Urban Soundscape Augmentation
description: Leveraging probabilistic AI for masker selection
image: 
---

2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) [[IEEE Xplore]](https://ieeexplore.ieee.org/document/9746897)

Soundscape augmentation, which involves the addition of sounds known as "maskers" to a given soundscape, is a human-centric urban noise mitigation measure aimed at improving the overall sound-scape quality. However, the choice of maskers is often predicated on laborious processes and is inflexible to the time-varying nature of real-world soundscapes. Owing to the perceptual uniqueness of each soundscape and the inherent subjectiveness of human perception, we propose a probabilistic perceptual attribute predictor (PPAP) that predicts parameters of random distributions as outputs instead of a single deterministic value. Using the PPAP, we developed a novel automatic masker selection system (AMSS), which selects optimal masker candidates based on the predicted distribution of the ISO 12913-3 Pleasantness score for a given soundscape. Via a largescale listening test with 300 participants, we collected 12600 subjective responses, each to a unique augmented soundscape, to train the PPAP models in a 5-fold cross-validation scheme. Using a convolutional recurrent neural network backbone and experimenting with several variants of the attention mechanism for the PPAP, we evaluated the proposed system on a blind test set with 48 unseen augmented soundscapes to assess the effectiveness of the probabilistic output scheme over traditional deterministic systems.
