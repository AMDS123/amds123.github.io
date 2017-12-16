---
layout: post
title: "A Fixed-Point Model for Pancreas Segmentation in Abdominal CT Scans"
date: 2017-06-21 04:00:59
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Yuyin Zhou, Lingxi Xie, Wei Shen, Yan Wang, Elliot K. Fishman, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have been widely adopted for automatic organ segmentation from abdominal CT scans. However, the segmentation accuracy of some small organs (e.g., the pancreas) is sometimes below satisfaction, arguably because deep networks are easily disrupted by the complex and variable background regions which occupies a large fraction of the input volume. In this paper, we formulate this problem into a fixed-point model which uses a predicted segmentation mask to shrink the input region. This is motivated by the fact that a smaller input region often leads to more accurate segmentation. In the training process, we use the ground-truth annotation to generate accurate input regions and optimize network weights. On the testing stage, we fix the network parameters and update the segmentation results in an iterative manner. We evaluate our approach on the NIH pancreas segmentation dataset, and outperform the state-of-the-art by more than 4%, measured by the average Dice-S{\o}rensen Coefficient (DSC). In addition, we report 62.43% DSC in the worst case, which guarantees the reliability of our approach in clinical applications.

##### Abstract (translated by Google)
深部神经网络已广泛应用于腹部CT扫描自动器官分割。然而，一些小器官（例如胰腺）的分割准确性有时低于满意度，这可以认为是因为深度网络容易被复杂且可变的背景区域占据大部分输入体积而中断。在本文中，我们将这个问题制定成一个定点模型，它使用一个预测分割蒙版缩小输入区域。这是由于一个较小的输入区域通常会导致更精确的分割。在训练过程中，我们使用地面真实注释来生成准确的输入区域并优化网络权重。在测试阶段，我们修复网络参数，并以迭代方式更新分割结果。我们在NIH胰腺分割数据集上评估了我们的方法，并且通过平均Dice-S（\ o \ o）rensen系数（DSC）测量超过了现有技术的4％以上。此外，我们在最坏的情况下报告62.43％DSC，这保证了我们在临床应用中的可靠性。

##### URL
[https://arxiv.org/abs/1612.08230](https://arxiv.org/abs/1612.08230)

##### PDF
[https://arxiv.org/pdf/1612.08230](https://arxiv.org/pdf/1612.08230)

