---
layout: post
title: "ScarGAN: Chained Generative Adversarial Networks to Simulate Pathological Tissue on Cardiovascular MR Scans"
date: 2018-08-14 01:10:00
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Prediction
author: Felix Lau, Tom Hendriks, Jesse Lieman-Sifry, Berk Norman, Sean Sall, Daniel Golden
mathjax: true
---

* content
{:toc}

##### Abstract
Medical images with specific pathologies are scarce, but a large amount of data is usually required for a deep convolutional neural network (DCNN) to achieve good accuracy. We consider the problem of segmenting the left ventricular (LV) myocardium on late gadolinium enhancement (LGE) cardiovascular magnetic resonance (CMR) scans of which only some of the scans have scar tissue. We propose ScarGAN to simulate scar tissue on healthy myocardium using chained generative adversarial networks (GAN). Our novel approach factorizes the simulation process into 3 steps: 1) a mask generator to simulate the shape of the scar tissue; 2) a domain-specific heuristic to produce the initial simulated scar tissue from the simulated shape; 3) a refining generator to add details to the simulated scar tissue. Unlike other approaches that generate samples from scratch, we simulate scar tissue on normal scans resulting in highly realistic samples. We show that experienced radiologists are unable to distinguish between real and simulated scar tissue. Training a U-Net with additional scans with scar tissue simulated by ScarGAN increases the percentage of scar pixels correctly included in LV myocardium prediction from 75.9% to 80.5%.

##### Abstract (translated by Google)
具有特定病理的医学图像很少，但是通常需要大量数据用于深度卷积神经网络（DCNN）以获得良好的准确性。我们考虑在晚期钆增强（LGE）心血管磁共振（CMR）扫描中分割左心室（LV）心肌的问题，其中仅一些扫描具有瘢痕组织。我们建议ScarGAN使用链式生成对抗网络（GAN）模拟健康心肌上的瘢痕组织。我们的新方法将模拟过程分为3个步骤：1）模拟疤痕组织形状的面罩发生器; 2）特定领域的启发式，从模拟形状产生初始模拟瘢痕组织; 3）精炼发生器，以向模拟的瘢痕组织添加细节。与从头开始生成样本的其他方法不同，我们在正常扫描中模拟瘢痕组织，从而产生高度逼真的样本。我们表明，有经验的放射科医师无法区分真实和模拟的瘢痕组织。通过ScarGAN模拟的瘢痕组织进行额外扫描训练U-Net，将LV心肌预测中正确包含的瘢痕像素百分比从75.9％提高到80.5％。

##### URL
[http://arxiv.org/abs/1808.04500](http://arxiv.org/abs/1808.04500)

##### PDF
[http://arxiv.org/pdf/1808.04500](http://arxiv.org/pdf/1808.04500)

