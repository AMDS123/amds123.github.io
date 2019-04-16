---
layout: post
title: "Reverse Attention for Salient Object Detection"
date: 2019-04-15 14:46:46
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Attention CNN Deep_Learning Prediction Detection
author: Shuhan Chen, Xiuli Tan, Ben Wang, Xuelong Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Benefit from the quick development of deep learning techniques, salient object detection has achieved remarkable progresses recently. However, there still exists following two major challenges that hinder its application in embedded devices, low resolution output and heavy model weight. To this end, this paper presents an accurate yet compact deep network for efficient salient object detection. More specifically, given a coarse saliency prediction in the deepest layer, we first employ residual learning to learn side-output residual features for saliency refinement, which can be achieved with very limited convolutional parameters while keep accuracy. Secondly, we further propose reverse attention to guide such side-output residual learning in a top-down manner. By erasing the current predicted salient regions from side-output features, the network can eventually explore the missing object parts and details which results in high resolution and accuracy. Experiments on six benchmark datasets demonstrate that the proposed approach compares favorably against state-of-the-art methods, and with advantages in terms of simplicity, efficiency (45 FPS) and model size (81 MB).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.09940](https://arxiv.org/abs/1807.09940)

##### PDF
[https://arxiv.org/pdf/1807.09940](https://arxiv.org/pdf/1807.09940)

