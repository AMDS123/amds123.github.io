---
layout: post
title: "Neural Affine Grayscale Image Denoising"
date: 2017-09-17 14:44:07
categories: arXiv_CV
tags: arXiv_CV
author: Sungmin Cha, Taesup Moon
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new grayscale image denoiser, dubbed as Neural Affine Image Denoiser (Neural AIDE), which utilizes neural network in a novel way. Unlike other neural network based image denoising methods, which typically apply simple supervised learning to learn a mapping from a noisy patch to a clean patch, we formulate to train a neural network to learn an \emph{affine} mapping that gets applied to a noisy pixel, based on its context. Our formulation enables both supervised training of the network from the labeled training dataset and adaptive fine-tuning of the network parameters using the given noisy image subject to denoising. The key tool for devising Neural AIDE is to devise an estimated loss function of the MSE of the affine mapping, solely based on the noisy data. As a result, our algorithm can outperform most of the recent state-of-the-art methods in the standard benchmark datasets. Moreover, our fine-tuning method can nicely overcome one of the drawbacks of the patch-level supervised learning methods in image denoising; namely, a supervised trained model with a mismatched noise variance can be mostly corrected as long as we have the matched noise variance during the fine-tuning step.

##### Abstract (translated by Google)
我们提出了一种新的灰度图像降噪器，被称为神经仿射图像降噪器（Neural AIDE），它以一种新颖的方式利用神经网络。与其他基于神经网络的图像去噪方法（通常应用简单的监督学习来学习从噪声补丁到干净的补丁的映射）不同，我们制定了训练神经网络来学习适用于噪声的“仿射”映射像素，基于其上下文。我们的公式使得从有标记的训练数据集对网络进行有监督的训练，并且使用给定的噪声图像进行去噪，自适应地微调网络参数。设计神经AIDE的关键工具是设计一个单独基于噪声数据的仿射映射的MSE的估计损失函数。因此，我们的算法可以胜过标准基准数据集中最新的最新方法。而且，我们的微调方法很好地克服了图像去噪中斑块级监督学习方法的一个缺点，即，只要在微调步骤中具有匹配的噪声方差，具有不匹配的噪声方差的受监督训练模型可以被大部分校正。

##### URL
[https://arxiv.org/abs/1709.05672](https://arxiv.org/abs/1709.05672)

##### PDF
[https://arxiv.org/pdf/1709.05672](https://arxiv.org/pdf/1709.05672)

