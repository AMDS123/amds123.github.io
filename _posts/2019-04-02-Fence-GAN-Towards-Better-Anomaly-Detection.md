---
layout: post
title: "Fence GAN: Towards Better Anomaly Detection"
date: 2019-04-02 04:36:15
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Classification Detection
author: Cuong Phuc Ngo, Amadeus Aristo Winarto, Connie Kou Khor Li, Sojeong Park, Farhan Akram, Hwee Kuan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Anomaly detection is a classical problem where the aim is to detect anomalous data that do not belong to the normal data distribution. Current state-of-the-art methods for anomaly detection on complex high-dimensional data are based on the generative adversarial network (GAN). However, the traditional GAN loss is not directly aligned with the anomaly detection objective: it encourages the distribution of the generated samples to overlap with the real data and so the resulting discriminator has been found to be ineffective as an anomaly detector. In this paper, we propose simple modifications to the GAN loss such that the generated samples lie at the boundary of the real data distribution. With our modified GAN loss, our anomaly detection method, called Fence GAN (FGAN), directly uses the discriminator score as an anomaly threshold. Our experimental results using the MNIST, CIFAR10 and KDD99 datasets show that Fence GAN yields the best anomaly classification accuracy compared to state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01209](https://arxiv.org/abs/1904.01209)

##### PDF
[https://arxiv.org/pdf/1904.01209](https://arxiv.org/pdf/1904.01209)

