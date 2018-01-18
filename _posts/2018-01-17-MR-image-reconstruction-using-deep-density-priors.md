---
layout: post
title: "MR image reconstruction using deep density priors"
date: 2018-01-17 13:42:41
categories: arXiv_CV
tags: arXiv_CV Regularization Inference Deep_Learning
author: Kerem C. Tezcan, Christian F. Baumgartner, Ender Konukoglu
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: MR image reconstruction exploits regularization to compensate for missing k-space data. In this work, we propose to learn the probability distribution of MR image patches with neural networks and use this distribution as prior information constraining images during reconstruction, effectively employing it as regularization. 
 Methods: We use variational autoencoders (VAE) to learn the distribution of MR image patches, which models the high-dimensional distribution by a latent parameter model of lower dimensions in a non-linear fashion. The proposed algorithm uses the learned prior in a Maximum-A-Posteriori estimation formulation. We evaluate the proposed reconstruction method with T1 weighted images and also apply our method on images with white matter lesions. 
 Results: Visual evaluation of the samples showed that the VAE algorithm can approximate the distribution of MR patches well. The proposed reconstruction algorithm using the VAE prior produced high quality reconstructions. The algorithm achieved normalized RMSE, CNR and CN values of 2.77\%, 0.43, 0.11; 4.29\%, 0.43, 0.11, 6.36\%, 0.47, 0.11 and 10.00\%, 0.42, 0.10 for undersampling ratios of 2, 3, 4 and 5, respectively, where it outperformed most of the alternative methods. In the experiments on images with white matter lesions, the method faithfully reconstructed the lesions. 
 Conclusion: We introduced a novel method for MR reconstruction, which takes a new perspective on regularization by using priors learned by neural networks. Results suggest the method compares favorably against the other evaluated methods and can reconstruct lesions as well. 
 Keywords: Reconstruction, MRI, prior probability, MAP estimation, machine learning, variational inference, deep learning

##### Abstract (translated by Google)
目的：MR图像重建利用正则化来补偿丢失的k空间数据。在这项工作中，我们提出用神经网络来学习MR图像块的概率分布，并将这种分布作为先验信息在重构过程中约束图像，有效地将其用作正则化。
 方法：使用变分自编码器（VAE）学习MR图像块的分布，用非线性方式用较低维的潜在参数模型对高维分布进行建模。所提出的算法使用最大后验估计公式中的学习先验。我们评估所提出的重建方法与T1加权图像，并应用我们的方法在图像与白质病变。
 结果：样本的视觉评估表明，VAE算法可以很好地近似MR贴片的分布。所提出的使用VAE的重建算法先前产生了高质量的重构。该算法实现了归一化的RMSE，CNR和CN值分别为2.77 \％，0.43,0.11;对于2,3,4和5的欠采样比，分别为4.29％，0.43％，0.11％，6.36％，0.47％，0.11％和10.00％，0.42％，0.10％，其中超过了大多数替代方法。在有白质病变的图像实验中，该方法忠实地重建病变。
 结论：本文介绍了一种新的MR重建方法，该方法利用神经网络学习的先验知识，对正则化有了新的认识。结果提示该方法与其他评估方法相比有利，并且可以重建病变。
 关键词：重建，MRI，先验概率，MAP估计，机器学习，变分推理，深度学习

##### URL
[http://arxiv.org/abs/1711.11386](http://arxiv.org/abs/1711.11386)

##### PDF
[http://arxiv.org/pdf/1711.11386](http://arxiv.org/pdf/1711.11386)

