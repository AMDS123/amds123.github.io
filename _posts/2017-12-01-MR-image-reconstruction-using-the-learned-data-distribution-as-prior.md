---
layout: post
title: "MR image reconstruction using the learned data distribution as prior"
date: 2017-12-01 10:34:44
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Kerem C. Tezcan, Christian F. Baumgartner, Ender Konukoglu
mathjax: true
---

* content
{:toc}

##### Abstract
MR image reconstruction from undersampled data exploits priors to compensate for missing k-space data. This has previously been achieved by using regularization methods, such as TV and wavelets, or data adaptive methods, such as dictionary learning. We propose to explicitly learn the probability distribution of MR image patches and to constrain patches to have a high probability according to this distribution in reconstruction, effectively employing it as the prior. We use variational autoencoders (VAE) to learn the distribution of MR image patches. This high dimensional distribution is modelled by a latent parameter model of lower dimensions in a non-linear fashion. We develop a reconstruction algorithm that uses the learned prior in a Maximum-A-Posteriori estimation formulation. We evaluate the proposed method with T1 weighted images and compare it to existing alternatives. We also apply our method on images with white matter lesions. Visual evaluation of the samples drawn from the learned model showed that the VAE algorithm was able to approximate the distribution of MR image patches. Furthermore, the reconstruction algorithm using the approximate distribution produced qualitatively better results. The proposed technique achieved RMSE, CNR and CN values of 2.77%, 0.43, 0.11 and 4.29%, 0.43, 0.11 for undersampling ratios of 2 and 3, respectively. It outperformed other evaluated methods in terms of used metrics. In the experiments on images with white matter lesions, the method faithfully reconstructed the lesions. We introduced a novel method for MR reconstruction, which takes a new perspective on regularization by learning priors. Results suggest the method compares favorably against TV and dictionary based methods as well as the neural-network based ADMM-Net in terms of the RMSE, CNR and CN and perceptual image quality and can reconstruct lesions as well.

##### Abstract (translated by Google)
来自欠采样数据的MR图像重构利用先验来补偿丢失的k空间数据。这已经通过使用诸如电视和小波之类的正则化方法或诸如字典学习之类的数据自适应方法来实现。我们建议明确学习MR图像块的概率分布，并根据这种分布在重建中约束块的概率很高，有效地将其用作先验分布。我们使用变分自动编码器（VAE）来学习MR图像片的分布。这种高维分布通过非线性方式的较低维的潜在参数模型来建模。我们开发了一种重建算法，使用最大后验估计公式中的学习先验。我们评估提出的方法与T1加权图像，并将其与现有的替代方案进行比较。我们也应用我们的方法对白质病变的图像。从学习模型中抽取的样本的视觉评估显示，VAE算法能够近似MR图像片的分布。此外，使用近似分布的重建算法产生了定性的更好结果。对于2和3的欠采样比，所提出的技术分别实现了2.77％，0.43％，0.11％和4.29％，0.43％，0.11％的RMSE，CNR和CN值。它在使用的度量方面胜过了其他评估方法。在有白质病变的图像实验中，该方法忠实地重建病变。我们引入了一种新的MR重建方法，通过学习先验，从正规化的角度出发，结果表明，该方法与基于TV和字典的方法以及基于神经网络的ADMM-Net方法在RMSE，CNR和CN方面以及感知图像质量方面相比，可以更好地重建病变。

##### URL
[https://arxiv.org/abs/1711.11386](https://arxiv.org/abs/1711.11386)

##### PDF
[https://arxiv.org/pdf/1711.11386](https://arxiv.org/pdf/1711.11386)

