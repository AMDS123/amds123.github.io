---
layout: post
title: "GAN-based Multiple Adjacent Brain MRI Slice Reconstruction for Unsupervised Alzheimer's Disease Diagnosis"
date: 2019-06-14 10:26:18
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Detection
author: Changhee Han, Leonardo Rundo, Kohei Murao, Zoltán Ádám Milacski, Kazuki Umemoto, Hideki Nakayama, Shin'ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Leveraging large-scale healthy datasets, unsupervised learning can discover various unseen diseases without any annotation. Towards this, unsupervised methods reconstruct a single medical image to detect outliers either in the learned feature space or from high reconstruction loss. However, without considering continuity between multiple adjacent images, they cannot directly discriminate diseases composed of the accumulation of subtle anatomical anomalies, such as Alzheimer's Disease (AD). Moreover, no study shows how unsupervised anomaly detection is associated with disease stages. Therefore, we propose a two-step method using Generative Adversarial Network-based multiple adjacent brain MRI slice reconstruction to detect AD at various stages: (Reconstruction) Wasserstein loss with Gradient Penalty + L1 loss---trained on 3 healthy brain MRI slices to reconstruct the next 3 ones---reconstructs unseen healthy/AD cases; (Diagnosis) Average/Maximum loss (e.g., L2 loss) per scan discriminates them, comparing the reconstructed/ground truth images. The results show that we can reliably detect AD at a very early stage (i.e., Area Under the Curve (AUC) 0.780) while also detecting AD at a late stage (i.e., AUC 0.917) much more accurately; since our method is unsupervised, it should also discover and alert any anomalies including rare disease.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06114](https://arxiv.org/abs/1906.06114)

##### PDF
[https://arxiv.org/pdf/1906.06114](https://arxiv.org/pdf/1906.06114)

