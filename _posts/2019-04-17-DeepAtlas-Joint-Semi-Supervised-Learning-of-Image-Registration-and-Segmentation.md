---
layout: post
title: "DeepAtlas: Joint Semi-Supervised Learning of Image Registration and Segmentation"
date: 2019-04-17 19:33:37
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Zhenlin Xu, Marc Niethammer
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) are state-of-the-art for semantic image segmentation, but typically require many labeled training samples. Obtaining 3D segmentations of medical images for supervised training is difficult and labor intensive. Motivated by classical approaches for joint segmentation and registration we therefore propose a deep learning framework that jointly learns networks for image registration and image segmentation. In contrast to previous work on deep unsupervised image registration, which showed the benefit of weak supervision via image segmentations, our approach can use existing segmentations when available and computes them via the segmentation network otherwise, thereby providing the same registration benefit. Conversely, segmentation network training benefits from the registration, which essentially provides a realistic form of data augmentation. Experiments on knee and brain 3D magnetic resonance (MR) images show that our approach achieves large simultaneous improvements of segmentation and registration accuracy (over independently trained networks) and allows training high-quality models with very limited training data. Specifically, in a one-shot-scenario (with only one manually labeled image) our approach increases Dice scores (%) over an unsupervised registration network by 2.7 and 1.8 on the knee and brain images respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08465](http://arxiv.org/abs/1904.08465)

##### PDF
[http://arxiv.org/pdf/1904.08465](http://arxiv.org/pdf/1904.08465)

