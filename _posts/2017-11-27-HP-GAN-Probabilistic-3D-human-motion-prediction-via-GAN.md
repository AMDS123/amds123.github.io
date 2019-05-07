---
layout: post
title: "HP-GAN: Probabilistic 3D human motion prediction via GAN"
date: 2017-11-27 07:07:11
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Prediction
author: Emad Barsoum, John Kender, Zicheng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting and understanding human motion dynamics has many applications, such as motion synthesis, augmented reality, security, and autonomous vehicles. Due to the recent success of generative adversarial networks (GAN), there has been much interest in probabilistic estimation and synthetic data generation using deep neural network architectures and learning algorithms. We propose a novel sequence-to-sequence model for probabilistic human motion prediction, trained with a modified version of improved Wasserstein generative adversarial networks (WGAN-GP), in which we use a custom loss function designed for human motion prediction. Our model, which we call HP-GAN, learns a probability density function of future human poses conditioned on previous poses. It predicts multiple sequences of possible future human poses, each from the same input sequence but a different vector z drawn from a random distribution. Furthermore, to quantify the quality of the non-deterministic predictions, we simultaneously train a motion-quality-assessment model that learns the probability that a given skeleton sequence is a real human motion. We test our algorithm on two of the largest skeleton datasets: NTURGB-D and Human3.6M. We train our model on both single and multiple action types. Its predictive power for long-term motion estimation is demonstrated by generating multiple plausible futures of more than 30 frames from just 10 frames of input. We show that most sequences generated from the same input have more than 50\% probabilities of being judged as a real human sequence. We will release all the code used in this paper to Github.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.09561](https://arxiv.org/abs/1711.09561)

##### PDF
[https://arxiv.org/pdf/1711.09561](https://arxiv.org/pdf/1711.09561)

