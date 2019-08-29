---
layout: post
title: "Complex Deep Learning Models for Denoising of Human Heart ECG signals"
date: 2019-08-27 19:14:32
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning
author: Corneliu Arsene
mathjax: true
---

* content
{:toc}

##### Abstract
Effective and powerful methods for denoising real electrocardiogram (ECG) signals are important for wearable sensors and devices. Deep Learning (DL) models have been used extensively in image processing and other domains with great success but only very recently have been used in processing ECG signals. This paper presents several DL models namely Convolutional Neural Networks (CNNs), Long Short-Term Memory (LSTM), Restricted Boltzmann Machine (RBM) together with the more conventional filtering methods (low pass filtering, high pass filtering, Notch filtering) and the standard wavelet-based technique for denoising EEG signals. These methods are trained, tested and evaluated on different synthetic and real ECG datasets taken from the MIT PhysioNet database and for different simulation conditions (i.e. various lengths of the ECG signals, single or multiple records). The results show the CNN model is a performant model that can be used for off-line denoising ECG applications where it is satisfactory to train on a clean part of an ECG signal from an ECG record, and then to test on the same ECG signal, which would have some high level of noise added to it. However, for real-time applications or near-real time applications, this task becomes more cumbersome, as the clean part of an ECG signal is very probable to be very limited in size. Therefore the solution put forth in this work is to train a CNN model on 1 second ECG noisy artificial multiple heartbeat data (i.e. ECG at effort), which was generated in a first instance based on few sequences of real signal heartbeat ECG data (i.e. ECG at rest). Afterwards it would be possible to use the trained CNN model in real life situations to denoise the ECG signal.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10417](http://arxiv.org/abs/1908.10417)

##### PDF
[http://arxiv.org/pdf/1908.10417](http://arxiv.org/pdf/1908.10417)

