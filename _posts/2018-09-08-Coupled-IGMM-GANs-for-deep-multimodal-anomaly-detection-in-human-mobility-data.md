---
layout: post
title: "Coupled IGMM-GANs for deep multimodal anomaly detection in human mobility data"
date: 2018-09-08 01:11:10
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Detection
author: Kathryn Gray, Daniel Smolyak, Sarkhan Badirli, George Mohler
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting anomalous activity in human mobility data has a number of applications including road hazard sensing, telematic based insurance, and fraud detection in taxi services and ride sharing. In this paper we address two challenges that arise in the study of anomalous human trajectories: 1) a lack of ground truth data on what defines an anomaly and 2) the dependence of existing methods on significant pre-processing and feature engineering. While generative adversarial networks seem like a natural fit for addressing these challenges, we find that existing GAN based anomaly detection algorithms perform poorly due to their inability to handle multimodal patterns. For this purpose we introduce an infinite Gaussian mixture model coupled with (bi-directional) generative adversarial networks, IGMM-GAN, that is able to generate synthetic, yet realistic, human mobility data and simultaneously facilitates multimodal anomaly detection. Through estimation of a generative probability density on the space of human trajectories, we are able to generate realistic synthetic datasets that can be used to benchmark existing anomaly detection methods. The estimated multimodal density also allows for a natural definition of outlier that we use for detecting anomalous trajectories. We illustrate our methodology and its improvement over existing GAN anomaly detection on several human mobility datasets, along with MNIST.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.02728](https://arxiv.org/abs/1809.02728)

##### PDF
[https://arxiv.org/pdf/1809.02728](https://arxiv.org/pdf/1809.02728)

