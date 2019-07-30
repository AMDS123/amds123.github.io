---
layout: post
title: "DUP-Net: Denoiser and Upsampler Network for 3D Adversarial Point Clouds Defense"
date: 2019-07-29 15:12:54
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Face Classification
author: Hang Zhou, Kejiang Chen, Weiming Zhang, Han Fang, Wenbo Zhou, Nenghai Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are vulnerable to adversarial examples, which poses a threat to their application in security sensitive systems. We propose a Denoiser and UPsampler Network (DUP-Net) structure as defenses for 3D adversarial point cloud classification, where the two modules reconstruct surface smoothness by dropping or adding points. In this paper, statistical outlier removal (SOR) and a data-driven upsampling network are considered as denoiser and upsampler respectively. Compared with baseline defenses, DUP-Net has three advantages. First, with DUP-Net as a defense, the target model is more robust to white-box adversarial attacks. Second, the statistical outlier removal provides added robustness since it is a non-differentiable denoising operation. Third, the upsampler network can be trained on a small dataset and defends well against adversarial attacks generated from other point cloud datasets. We conduct various experiments to validate that DUP-Net is very effective as defense in practice. Our best defense eliminates 83.8% of C&amp;W and l_2 loss based attack (point shifting), 50.0% of C&amp;W and Hausdorff distance loss based attack (point adding) and 9.0% of saliency map based attack (point dropping) under 200 dropped points on PointNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11017](http://arxiv.org/abs/1812.11017)

##### PDF
[http://arxiv.org/pdf/1812.11017](http://arxiv.org/pdf/1812.11017)

