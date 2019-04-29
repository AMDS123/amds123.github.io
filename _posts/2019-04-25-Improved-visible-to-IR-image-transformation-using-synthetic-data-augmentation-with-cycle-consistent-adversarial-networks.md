---
layout: post
title: "Improved visible to IR image transformation using synthetic data augmentation with cycle-consistent adversarial networks"
date: 2019-04-25 23:12:52
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Recognition
author: Kyongsik Yun, Kevin Yu, Joseph Osborne, Sarah Eldin, Luan Nguyen, Alexander Huyen, Thomas Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Infrared (IR) images are essential to improve the visibility of dark or camouflaged objects. Object recognition and segmentation based on a neural network using IR images provide more accuracy and insight than color visible images. But the bottleneck is the amount of relevant IR images for training. It is difficult to collect real-world IR images for special purposes, including space exploration, military and fire-fighting applications. To solve this problem, we created color visible and IR images using a Unity-based 3D game editor. These synthetically generated color visible and IR images were used to train cycle consistent adversarial networks (CycleGAN) to convert visible images to IR images. CycleGAN has the advantage that it does not require precisely matching visible and IR pairs for transformation training. In this study, we discovered that additional synthetic data can help improve CycleGAN performance. Neural network training using real data (N = 20) performed more accurate transformations than training using real (N = 10) and synthetic (N = 10) data combinations. The result indicates that the synthetic data cannot exceed the quality of the real data. Neural network training using real (N = 10) and synthetic (N = 100) data combinations showed almost the same performance as training using real data (N = 20). At least 10 times more synthetic data than real data is required to achieve the same performance. In summary, CycleGAN is used with synthetic data to improve the IR image conversion performance of visible images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11620](http://arxiv.org/abs/1904.11620)

##### PDF
[http://arxiv.org/pdf/1904.11620](http://arxiv.org/pdf/1904.11620)

