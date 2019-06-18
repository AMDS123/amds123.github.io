---
layout: post
title: "Rethinking Monocular Depth Estimation with Adversarial Training"
date: 2019-06-15 18:37:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Richard Chen, Faisal Mahmood, Alan Yuille, Nicholas J. Durr
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular depth estimation is an extensively studied computer vision problem with a vast variety of applications. Deep learning-based methods have demonstrated promise for both supervised and unsupervised depth estimation from monocular images. Most existing approaches treat depth estimation as a regression problem with a local pixel-wise loss function. In this work, we innovate beyond existing approaches by using adversarial training to learn a context-aware, non-local loss function. Such an approach penalizes the joint configuration of predicted depth values at the patch-level instead of the pixel-level, which allows networks to incorporate more global information. In this framework, the generator learns a mapping between RGB images and its corresponding depth map, while the discriminator learns to distinguish depth map and RGB pairs from ground truth. This conditional GAN depth estimation framework is stabilized using spectral normalization to prevent mode collapse when learning from diverse datasets. We test this approach using a diverse set of generators that include U-Net and joint CNN-CRF. We benchmark this approach on the NYUv2, Make3D and KITTI datasets, and observe that adversarial training reduces relative error by several fold, achieving state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.07528](http://arxiv.org/abs/1808.07528)

##### PDF
[http://arxiv.org/pdf/1808.07528](http://arxiv.org/pdf/1808.07528)

