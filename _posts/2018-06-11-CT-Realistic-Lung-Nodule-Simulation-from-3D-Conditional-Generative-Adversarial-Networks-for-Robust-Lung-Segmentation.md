---
layout: post
title: "CT-Realistic Lung Nodule Simulation from 3D Conditional Generative Adversarial Networks for Robust Lung Segmentation"
date: 2018-06-11 15:19:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Deep_Learning Quantitative
author: Dakai Jin, Ziyue Xu, Youbao Tang, Adam P. Harrison, Daniel J. Mollura
mathjax: true
---

* content
{:toc}

##### Abstract
Data availability plays a critical role for the performance of deep learning systems. This challenge is especially acute within the medical image domain, particularly when pathologies are involved, due to two factors: 1) limited number of cases, and 2) large variations in location, scale, and appearance. In this work, we investigate whether augmenting a dataset with artificially generated lung nodules can improve the robustness of the progressive holistically nested network (P-HNN) model for pathological lung segmentation of CT scans. To achieve this goal, we develop a 3D generative adversarial network (GAN) that effectively learns lung nodule property distributions in 3D space. In order to embed the nodules within their background context, we condition the GAN based on a volume of interest whose central part containing the nodule has been erased. To further improve realism and blending with the background, we propose a novel multi-mask reconstruction loss. We train our method on over 1000 nodules from the LIDC dataset. Qualitative results demonstrate the effectiveness of our method compared to the state-of-art. We then use our GAN to generate simulated training images where nodules lie on the lung border, which are cases where the published P-HNN model struggles. Qualitative and quantitative results demonstrate that armed with these simulated images, the P-HNN model learns to better segment lung regions under these challenging situations. As a result, our system provides a promising means to help overcome the data paucity that commonly afflicts medical imaging.

##### Abstract (translated by Google)
数据可用性对深度学习系统的性能起着至关重要的作用。这一挑战在医学图像领域尤其突出，特别是涉及病理时，由于两个因素：1）病例数量有限，2）位置，规模和外观变化很大。在这项工作中，我们调查是否用人为生成的肺结节增加数据集可以提高CT扫描病理肺分割的渐进整体嵌套网络（P-HNN）模型的鲁棒性。为了实现这一目标，我们开发了3D生成对抗网络（GAN），可以有效地学习3D空间中的肺结节属性分布。为了将结节嵌入其背景环境中，我们基于其包含结节的中心部分已被擦除的感兴趣体积来调节GAN。为了进一步改善现实性和与背景的融合，我们提出了一种新颖的多重蒙版重建损失。我们从LIDC数据集中训练超过1000个结节的方法。定性结果证明了我们的方法与现有技术相比的有效性。然后，我们使用我们的GAN生成模拟训练图像，其中结节位于肺部边界，这是公布的P-HNN模型挣扎的情况。定性和定量结果表明，使用这些模拟图像，P-HNN模型学习在这些具有挑战性的情况下更好地分割肺区域。因此，我们的系统提供了一种有前途的方法来帮助克服通常影响医学成像的数据不足。

##### URL
[http://arxiv.org/abs/1806.04051](http://arxiv.org/abs/1806.04051)

##### PDF
[http://arxiv.org/pdf/1806.04051](http://arxiv.org/pdf/1806.04051)

