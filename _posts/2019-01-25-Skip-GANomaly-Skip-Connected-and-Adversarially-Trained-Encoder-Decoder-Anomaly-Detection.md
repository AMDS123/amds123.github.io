---
layout: post
title: "Skip-GANomaly: Skip Connected and Adversarially Trained Encoder-Decoder Anomaly Detection"
date: 2019-01-25 16:18:22
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Detection
author: Samet Ak&#xe7;ay, Amir Atapour-Abarghouei, Toby P. Breckon
mathjax: true
---

* content
{:toc}

##### Abstract
Despite inherent ill-definition, anomaly detection is a research endeavor of great interest within machine learning and visual scene understanding alike. Most commonly, anomaly detection is considered as the detection of outliers within a given data distribution based on some measure of normality. The most significant challenge in real-world anomaly detection problems is that available data is highly imbalanced towards normality (i.e. non-anomalous) and contains a most a subset of all possible anomalous samples - hence limiting the use of well-established supervised learning methods. By contrast, we introduce an unsupervised anomaly detection model, trained only on the normal (non-anomalous, plentiful) samples in order to learn the normality distribution of the domain and hence detect abnormality based on deviation from this model. Our proposed approach employs an encoder-decoder convolutional neural network with skip connections to thoroughly capture the multi-scale distribution of the normal data distribution in high-dimensional image space. Furthermore, utilizing an adversarial training scheme for this chosen architecture provides superior reconstruction both within high-dimensional image space and a lower-dimensional latent vector space encoding. Minimizing the reconstruction error metric within both the image and hidden vector spaces during training aids the model to learn the distribution of normality as required. Higher reconstruction metrics during subsequent test and deployment are thus indicative of a deviation from this normal distribution, hence indicative of an anomaly. Experimentation over established anomaly detection benchmarks and challenging real-world datasets, within the context of X-ray security screening, shows the unique promise of such a proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08954](http://arxiv.org/abs/1901.08954)

##### PDF
[http://arxiv.org/pdf/1901.08954](http://arxiv.org/pdf/1901.08954)

