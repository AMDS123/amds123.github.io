---
layout: post
title: "RAN4IQA: Restorative Adversarial Nets for No-Reference Image Quality Assessment"
date: 2017-12-14 20:37:49
categories: arXiv_CV
tags: arXiv_CV Adversarial QA GAN
author: Hongyu Ren, Diqi Chen, Yizhou Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by the free-energy brain theory, which implies that human visual system (HVS) tends to reduce uncertainty and restore perceptual details upon seeing a distorted image, we propose restorative adversarial net (RAN), a GAN-based model for no-reference image quality assessment (NR-IQA). RAN, which mimics the process of HVS, consists of three components: a restorator, a discriminator and an evaluator. The restorator restores and reconstructs input distorted image patches, while the discriminator distinguishes the reconstructed patches from the pristine distortion-free patches. After restoration, we observe that the perceptual distance between the restored and the distorted patches is monotonic with respect to the distortion level. We further define Gain of Restoration (GoR) based on this phenomenon. The evaluator predicts perceptual score by extracting feature representations from the distorted and restored patches to measure GoR. Eventually, the quality score of an input image is estimated by weighted sum of the patch scores. Experimental results on Waterloo Exploration, LIVE and TID2013 show the effectiveness and generalization ability of RAN compared to the state-of-the-art NR-IQA models.

##### Abstract (translated by Google)
受自由能脑理论的启发，人类视觉系统（HVS）倾向于减少不确定性并在看到失真图像时恢复感知细节，我们提出了恢复性对抗网络（RAN），一种基于GAN的无参考模型图像质量评估（NR-IQA）。 RAN模仿HVS的过程，由三部分组成：恢复器，鉴别器和评估器。修复者恢复和重建输入失真的图像块，而鉴别器区分重建的补丁和原始的无失真补丁。恢复后，我们观察到恢复和扭曲补丁之间的感知距离相对于失真水平是单调的。我们进一步根据这个现象来定义恢复增益（GoR）。评估者通过从失真和恢复的补丁中提取特征表示来预测感知分数以测量GoR。最后，输入图像的质量分数通过补丁分数的加权和来估计。 Waterloo Exploration，LIVE和TID2013的实验结果显示了RAN与最先进的NR-IQA模型相比的有效性和泛化能力。

##### URL
[http://arxiv.org/abs/1712.05444](http://arxiv.org/abs/1712.05444)

##### PDF
[http://arxiv.org/pdf/1712.05444](http://arxiv.org/pdf/1712.05444)

