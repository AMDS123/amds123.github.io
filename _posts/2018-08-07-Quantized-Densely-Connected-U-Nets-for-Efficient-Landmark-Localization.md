---
layout: post
title: "Quantized Densely Connected U-Nets for Efficient Landmark Localization"
date: 2018-08-07 03:22:44
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation
author: Zhiqiang Tang, Xi Peng, Shijie Geng, Lingfei Wu, Shaoting Zhang, Dimitris Metaxas
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose quantized densely connected U-Nets for efficient visual landmark localization. The idea is that features of the same semantic meanings are globally reused across the stacked U-Nets. This dense connectivity largely improves the information flow, yielding improved localization accuracy. However, a vanilla dense design would suffer from critical efficiency issue in both training and testing. To solve this problem, we first propose order-K dense connectivity to trim off long-distance shortcuts; then, we use a memory-efficient implementation to significantly boost the training efficiency and investigate an iterative refinement that may slice the model size in half. Finally, to reduce the memory consumption and high precision operations both in training and testing, we further quantize weights, inputs, and gradients of our localization network to low bit-width numbers. We validate our approach in two tasks: human pose estimation and face alignment. The results show that our approach achieves state-of-the-art localization accuracy, but using $\sim$70\% fewer parameters, $\sim$98\% less model size and saving $\sim$75\% training memory compared with other benchmark localizers. The code is available at https://github.com/zhiqiangdon/CU-Net.

##### Abstract (translated by Google)
在本文中，我们提出量子化密集连接的U-Nets，以实现有效的视觉地标定位。这个想法是在堆叠的U-Nets中全局重用相同语义含义的特征。这种密集的连接性极大地改善了信息流，从而提高了定位精度。然而，香草密集设计在训练和测试中都会遇到关键的效率问题。为了解决这个问题，我们首先提出了订单-K密集连接来修剪远程快捷方式;然后，我们使用内存有效的实现来显着提高训练效率，并研究可能将模型大小分成两半的迭代细化。最后，为了减少训练和测试中的内存消耗和高精度操作，我们进一步将我们的定位网络的权重，输入和梯度量化为低位宽数字。我们在两个任务中验证了我们的方法：人体姿势估计和面部对齐。结果表明，我们的方法达到了最先进的定位精度，但使用$ \ sim $ 70％以下的参数，$ \ sim $ 98 \％减去模型尺寸并节省$ \ sim $ 75 \％训练内存与其他相比基准定位器。该代码可在https://github.com/zhiqiangdon/CU-Net上找到。

##### URL
[http://arxiv.org/abs/1808.02194](http://arxiv.org/abs/1808.02194)

##### PDF
[http://arxiv.org/pdf/1808.02194](http://arxiv.org/pdf/1808.02194)

