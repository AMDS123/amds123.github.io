---
layout: post
title: "ID Preserving Generative Adversarial Network for Partial Latent Fingerprint Reconstruction"
date: 2018-07-31 19:20:49
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Recognition
author: Ali Dabouei, Sobhan Soleymani, Hadi Kazemi, Seyed Mehdi Iranmanesh, Jeremy Dawson, Nasser M. Nasrabadi
mathjax: true
---

* content
{:toc}

##### Abstract
Performing recognition tasks using latent fingerprint samples is often challenging for automated identification systems due to poor quality, distortion, and partially missing information from the input samples. We propose a direct latent fingerprint reconstruction model based on conditional generative adversarial networks (cGANs). Two modifications are applied to the cGAN to adapt it for the task of latent fingerprint reconstruction. First, the model is forced to generate three additional maps to the ridge map to ensure that the orientation and frequency information is considered in the generation process, and prevent the model from filling large missing areas and generating erroneous minutiae. Second, a perceptual ID preservation approach is developed to force the generator to preserve the ID information during the reconstruction process. Using a synthetically generated database of latent fingerprints, the deep network learns to predict missing information from the input latent samples. We evaluate the proposed method in combination with two different fingerprint matching algorithms on several publicly available latent fingerprint datasets. We achieved the rank-10 accuracy of 88.02\% on the IIIT-Delhi latent fingerprint database for the task of latent-to-latent matching and rank-50 accuracy of 70.89\% on the IIIT-Delhi MOLF database for the task of latent-to-sensor matching. Experimental results of matching reconstructed samples in both latent-to-sensor and latent-to-latent frameworks indicate that the proposed method significantly increases the matching accuracy of the fingerprint recognition systems for the latent samples.

##### Abstract (translated by Google)
由于质量差，失真以及来自输入样本的部分缺失信息，使用潜指纹样本执行识别任务对于自动识别系统而言通常是具有挑战性的。我们提出了一种基于条件生成对抗网络（cGAN）的直接潜指纹重建模型。对cGAN应用两种修改以使其适应潜在指纹重建的任务。首先，模型被迫生成三个额外的地图到脊图，以确保在生成过程中考虑方向和频率信息，并防止模型填充大的缺失区域并产生错误的细节。其次，开发了感知ID保存方法以迫使发生器在重建过程中保存ID信息。使用合成生成的潜指纹数据库，深层网络学习从输入潜在样本中预测缺失信息。我们在几个公开可用的潜指纹数据集上结合两种不同的指纹匹配算法来评估所提出的方法。我们在IIIT-Delhi潜在指纹数据库上获得了88.02％的等级10准确度，用于潜在匹配任务，并且在IIIT-Delhi MOLF数据库中为潜在任务达到70.89 \％的等级50准确度 - 传感器匹配。在潜在 - 传感器和潜 - 潜到框架中匹配重建样本的实验结果表明，所提出的方法显着提高了潜在样本的指纹识别系统的匹配精度。

##### URL
[https://arxiv.org/abs/1808.00035](https://arxiv.org/abs/1808.00035)

##### PDF
[https://arxiv.org/pdf/1808.00035](https://arxiv.org/pdf/1808.00035)

