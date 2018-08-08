---
layout: post
title: "SPG-Net: Segmentation Prediction and Guidance Network for Image Inpainting"
date: 2018-08-06 19:53:18
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
在本文中，我们专注于图像修复任务，旨在在给定上下文信息的情况下恢复不完整图像的缺失区域。深度生成模型的最新发展为图像合成和修复任务提供了有效的端到端框架，但是基于生成模型的现有方法不利用分割信息来约束对象形状，这通常导致模糊结果边界。为了解决这个问题，我们提出引入语义分割信息，它解开了图像修复的类间差异和类内变异。这导致在语义上不同的区域之间更清晰的恢复边界和在语义上一致的段内更好的纹理。我们的模型将图像修复过程分解为分割预测（SP-Net）和分割引导（SG-Net）两个步骤，首先预测缺失区域中的分割标签，然后生成分割引导的修复结果。对多个公共数据集的实验表明，我们的方法在优化图像修复质量方面优于现有方法，并且交互式分割指导为图像修复的多模态预测提供了可能性。

##### URL
[http://arxiv.org/abs/1805.03356](http://arxiv.org/abs/1805.03356)

##### PDF
[http://arxiv.org/pdf/1805.03356](http://arxiv.org/pdf/1805.03356)

