---
layout: post
title: "Domain Adaptation with L2 constraints for classifying images from different endoscope systems"
date: 2018-02-02 09:01:20
categories: arXiv_CV
tags: arXiv_CV
author: Toru Tamaki, Shoji Sonoyama, Takio Kurita, Tsubasa Hirakawa, Bisser Raytchev, Kazufumi Kaneda, Tetsushi Koide, Shigeto Yoshida, Hiroshi Mieno, Shinji Tanaka, Kazuaki Chayama
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a method for domain adaptation that extends the maximum margin domain transfer (MMDT) proposed by Hoffman et al., by introducing L2 distance constraints between samples of different domains; thus, our method is denoted as MMDTL2. Motivated by the differences between the images taken by narrow band imaging (NBI) endoscopic devices, we utilize different NBI devices as different domains and estimate the transformations between samples of different domains, i.e., image samples taken by different NBI endoscope systems. We first formulate the problem in the primal form, and then derive the dual form with much lesser computational costs as compared to the naive approach. From our experimental results using NBI image datasets from two different NBI endoscopic devices, we find that MMDTL2 is better than MMDT and also support vector machines without adaptation, especially when NBI image features are high-dimensional and the per-class training samples are greater than 20.

##### Abstract (translated by Google)
本文提出了一种扩展由Hoffman等人提出的最大边界域转移（MMDT）的域自适应方法，通过引入不同域样本之间的L2距离约束;因此，我们的方法被表示为MMDTL2。受窄带成像（NBI）内窥镜装置拍摄的图像之间的差异的驱动，我们利用不同的NBI装置作为不同的区域，并且估计不同区域的样本之间的转换，即，由不同的NBI内窥镜系统拍摄的图像样本。我们首先以原始形式来制定问题，然后导出与天真方法相比计算成本更低的双重形式。从我们使用来自两个不同的NBI内窥镜设备的NBI图像数据集的实验结果，我们发现MMDTL2优于MMDT，并且还支持没有自适应的矢量机，特别是当NBI图像特征是高维的并且每类训练样本大于20。

##### URL
[http://arxiv.org/abs/1611.02443](http://arxiv.org/abs/1611.02443)

##### PDF
[http://arxiv.org/pdf/1611.02443](http://arxiv.org/pdf/1611.02443)

