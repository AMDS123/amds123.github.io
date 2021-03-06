---
layout: post
title: "A Robust Approach for Securing Audio Classification Against Adversarial Attacks"
date: 2019-04-24 18:07:52
categories: arXiv_SD
tags: arXiv_SD Review Adversarial Classification Deep_Learning Prediction
author: Mohammad Esmaeilpour, Patrick Cardinal, Alessandro Lameiras Koerich
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial audio attacks can be considered as a small perturbation unperceptive to human ears that is intentionally added to the audio signal and causes a machine learning model to make mistakes. This poses a security concern about the safety of machine learning models since the adversarial attacks can fool such models toward the wrong predictions. In this paper we first review some strong adversarial attacks that may affect both audio signals and their 2D representations and evaluate the resiliency of the most common machine learning model, namely deep learning models and support vector machines (SVM) trained on 2D audio representations such as short time Fourier transform (STFT), discrete wavelet transform (DWT) and cross recurrent plot (CRP) against several state-of-the-art adversarial attacks. Next, we propose a novel approach based on pre-processed DWT representation of audio signals and SVM to secure audio systems against adversarial attacks. The proposed architecture has several preprocessing modules for generating and enhancing spectrograms including dimension reduction and smoothing. We extract features from small patches of the spectrograms using speeded up robust feature (SURF) algorithm which are further used to generate a codebook using the K-Means++ algorithm. Finally, codewords are used to train a SVM on the codebook of the SURF-generated vectors. All these steps yield to a novel approach for audio classification that provides a good trade-off between accuracy and resilience. Experimental results on three environmental sound datasets show the competitive performance of proposed approach compared to the deep neural networks both in terms of accuracy and robustness against strong adversarial attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10990](http://arxiv.org/abs/1904.10990)

##### PDF
[http://arxiv.org/pdf/1904.10990](http://arxiv.org/pdf/1904.10990)

