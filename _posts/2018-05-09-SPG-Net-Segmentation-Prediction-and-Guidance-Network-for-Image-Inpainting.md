---
layout: post
title: "SPG-Net: Segmentation Prediction and Guidance Network for Image Inpainting"
date: 2018-05-09 03:02:06
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction
author: Yuhang Song, Chao Yang, Yeji Shen, Peng Wang, Qin Huang, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we focus on image inpainting task, aiming at recovering the missing area of an incomplete image given the context information. Recent development in deep generative models enables an efficient end-to-end framework for image synthesis and inpainting tasks, but existing methods based on generative models don't exploit the segmentation information to constrain the object shapes, which usually lead to blurry results on the boundary. To tackle this problem, we propose to introduce the semantic segmentation information, which disentangles the inter-class difference and intra-class variation for image inpainting. This leads to much clearer recovered boundary between semantically different regions and better texture within semantically consistent segments. Our model factorizes the image inpainting process into segmentation prediction (SP-Net) and segmentation guidance (SG-Net) as two steps, which predict the segmentation labels in the missing area first, and then generate segmentation guided inpainting results. Experiments on multiple public datasets show that our approach outperforms existing methods in optimizing the image inpainting quality, and the interactive segmentation guidance provides possibilities for multi-modal predictions of image inpainting.

##### Abstract (translated by Google)
在本文中，我们关注图像修复任务，旨在根据上下文信息恢复不完整图像的缺失区域。最近深度生成模型的发展为图像合成和修补任务提供了一个有效的端到端框架，但基于生成模型的现有方法并未利用分割信息来约束目标形状，这通常会导致模糊的结果边界。针对这个问题，我们提出引入语义分割信息，从而解决图像修补中的类间差异和类内变异问题。这导致在语义上不同的区域之间恢复的边界更清晰并且在语义上一致的区段内具有更好的纹理。我们的模型将图像修复过程分解为分割预测（SP-Net）和分割指导（SG-Net）两个步骤，它们首先预测缺失区域中的分割标签，然后生成分割引导的修复结果。在多个公共数据集上进行的实验表明，我们的方法在优化图像修复质量方面优于现有方法，交互式分割指南为图像修复的多模态预测提供了可能性。

##### URL
[http://arxiv.org/abs/1805.03356](http://arxiv.org/abs/1805.03356)

##### PDF
[http://arxiv.org/pdf/1805.03356](http://arxiv.org/pdf/1805.03356)

