---
layout: post
title: "Singing Voice Separation Using a Deep Convolutional Neural Network Trained by Ideal Binary Mask and Cross Entropy"
date: 2018-12-04 08:47:41
categories: arXiv_AI
tags: arXiv_AI CNN Image_Classification Classification
author: Kin Wah Edward Lin, Balamurali B.T., Enyan Koh, Simon Lui, Dorien Herremans
mathjax: true
---

* content
{:toc}

##### Abstract
Separating a singing voice from its music accompaniment remains an important challenge in the field of music information retrieval. We present a unique neural network approach inspired by a technique that has revolutionized the field of vision: pixel-wise image classification, which we combine with cross entropy loss and pretraining of the CNN as an autoencoder on singing voice spectrograms. The pixel-wise classification technique directly estimates the sound source label for each time-frequency (T-F) bin in our spectrogram image, thus eliminating common pre- and postprocessing tasks. The proposed network is trained by using the Ideal Binary Mask (IBM) as the target output label. The IBM identifies the dominant sound source in each T-F bin of the magnitude spectrogram of a mixture signal, by considering each T-F bin as a pixel with a multi-label (for each sound source). Cross entropy is used as the training objective, so as to minimize the average probability error between the target and predicted label for each pixel. By treating the singing voice separation problem as a pixel-wise classification task, we additionally eliminate one of the commonly used, yet not easy to comprehend, postprocessing steps: the Wiener filter postprocessing. 
 The proposed CNN outperforms the first runner up in the Music Information Retrieval Evaluation eXchange (MIREX) 2016 and the winner of MIREX 2014 with a gain of 2.2702 ~ 5.9563 dB global normalized source to distortion ratio (GNSDR) when applied to the iKala dataset. An experiment with the DSD100 dataset on the full-tracks song evaluation task also shows that our model is able to compete with cutting-edge singing voice separation systems which use multi-channel modeling, data augmentation, and model blending.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01278](http://arxiv.org/abs/1812.01278)

##### PDF
[http://arxiv.org/pdf/1812.01278](http://arxiv.org/pdf/1812.01278)

