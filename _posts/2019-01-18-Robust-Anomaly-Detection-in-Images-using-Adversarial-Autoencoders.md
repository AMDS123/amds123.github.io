---
layout: post
title: "Robust Anomaly Detection in Images using Adversarial Autoencoders"
date: 2019-01-18 17:48:15
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Laura Beggel, Michael Pfeiffer, Bernd Bischl
mathjax: true
---

* content
{:toc}

##### Abstract
Reliably detecting anomalies in a given set of images is a task of high practical relevance for visual quality inspection, surveillance, or medical image analysis. Autoencoder neural networks learn to reconstruct normal images, and hence can classify those images as anomalies, where the reconstruction error exceeds some threshold. Here we analyze a fundamental problem of this approach when the training set is contaminated with a small fraction of outliers. We find that continued training of autoencoders inevitably reduces the reconstruction error of outliers, and hence degrades the anomaly detection performance. In order to counteract this effect, an adversarial autoencoder architecture is adapted, which imposes a prior distribution on the latent representation, typically placing anomalies into low likelihood-regions. Utilizing the likelihood model, potential anomalies can be identified and rejected already during training, which results in an anomaly detector that is significantly more robust to the presence of outliers during training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06355](http://arxiv.org/abs/1901.06355)

##### PDF
[http://arxiv.org/pdf/1901.06355](http://arxiv.org/pdf/1901.06355)

