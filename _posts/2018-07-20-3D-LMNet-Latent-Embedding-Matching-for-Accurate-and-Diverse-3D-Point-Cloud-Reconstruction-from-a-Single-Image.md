---
layout: post
title: "3D-LMNet: Latent Embedding Matching for Accurate and Diverse 3D Point Cloud Reconstruction from a Single Image"
date: 2018-07-20 11:32:02
categories: arXiv_CV
tags: arXiv_CV Embedding Quantitative
author: Priyanka Mandikal, Navaneet Murthy, Mayank Agarwal, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
3D reconstruction from single view images is an ill-posed problem. Inferring the hidden regions from self-occluded images is both challenging and ambiguous. We propose a two-pronged approach to address these issues. To better incorporate the data prior and generate meaningful reconstructions, we propose 3D-LMNet, a latent embedding matching approach for 3D reconstruction. We first train a 3D point cloud auto-encoder and then learn a mapping from the 2D image to the corresponding learnt embedding. To tackle the issue of uncertainty in the reconstruction, we predict multiple reconstructions that are consistent with the input view. This is achieved by learning a probablistic latent space with a novel view-specific diversity loss. Thorough quantitative and qualitative analysis is performed to highlight the significance of the proposed approach. We outperform state-of-the-art approaches on the task of single-view 3D reconstruction on both real and synthetic datasets while generating multiple plausible reconstructions, demonstrating the generalizability and utility of our approach.

##### Abstract (translated by Google)
单视图图像的3D重建是一个不适定的问题。从自遮挡图像中推断隐藏区域既具有挑战性又模糊不清。我们提出了一种双管齐下的方法来解决这些问题。为了更好地合并先前的数据并生成有意义的重建，我们提出了3D-LMNet，一种用于3D重建的潜在嵌入匹配方法。我们首先训练3D点云自动编码器，然后学习从2D图像到相应的学习嵌入的映射。为了解决重建中的不确定性问题，我们预测了与输入视图一致的多个重建。这是通过学习具有新颖视图特定多样性损失的概率潜在空间来实现的。进行彻底的定量和定性分析以突出所提出方法的重要性。我们在真实和合成数据集上的单视图3D重建任务上表现优于最先进的方法，同时生成多个合理的重建，展示了我们方法的普遍性和实用性。

##### URL
[http://arxiv.org/abs/1807.07796](http://arxiv.org/abs/1807.07796)

##### PDF
[http://arxiv.org/pdf/1807.07796](http://arxiv.org/pdf/1807.07796)

