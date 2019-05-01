---
layout: post
title: "Learning Raw Image Denoising with Bayer Pattern Unification and Bayer Preserving Augmentation"
date: 2019-04-29 21:01:40
categories: arXiv_CV
tags: arXiv_CV
author: Jiaming Liu, Chi-Hao Wu, Yuzhi Wang, Qin Xu, Yuqian Zhou, Haibin Huang, Chuan Wang, Shaofan Cai, Yifan Ding, Haoqiang Fan, Jue Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present new data pre-processing and augmentation techniques for DNN-based raw image denoising. Compared with traditional RGB image denoising, performing this task on direct camera sensor readings presents new challenges such as how to effectively handle various Bayer patterns from different data sources, and subsequently how to perform valid data augmentation with raw images. To address the first problem, we propose a Bayer pattern unification (BayerUnify) method to unify different Bayer patterns. This allows us to fully utilize a heterogeneous dataset to train a single denoising model instead of training one model for each pattern. Furthermore, while it is essential to augment the dataset to improve model generalization and performance, we discovered that it is error-prone to modify raw images by adapting augmentation methods designed for RGB images. Towards this end, we present a Bayer preserving augmentation (BayerAug) method as an effective approach for raw image augmentation. Combining these data processing technqiues with a modified U-Net, our method achieves a PSNR of 52.11 and a SSIM of 0.9969 in NTIRE 2019 Real Image Denoising Challenge, demonstrating the state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12945](http://arxiv.org/abs/1904.12945)

##### PDF
[http://arxiv.org/pdf/1904.12945](http://arxiv.org/pdf/1904.12945)

