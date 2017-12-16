---
layout: post
title: "Deep Convolutional Neural Networks with Merge-and-Run Mappings"
date: 2017-07-19 07:27:21
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Liming Zhao, Jingdong Wang, Xi Li, Zhuowen Tu, Wenjun Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
A deep residual network, built by stacking a sequence of residual blocks, is easy to train, because identity mappings skip residual branches and thus improve information flow. To further reduce the training difficulty, we present a simple network architecture, deep merge-and-run neural networks. The novelty lies in a modularized building block, merge-and-run block, which assembles residual branches in parallel through a merge-and-run mapping: Average the inputs of these residual branches (Merge), and add the average to the output of each residual branch as the input of the subsequent residual branch (Run), respectively. We show that the merge-and-run mapping is a linear idempotent function in which the transformation matrix is idempotent, and thus improves information flow, making training easy. In comparison to residual networks, our networks enjoy compelling advantages: they contain much shorter paths, and the width, i.e., the number of channels, is increased. We evaluate the performance on the standard recognition tasks. Our approach demonstrates consistent improvements over ResNets with the comparable setup, and achieves competitive results (e.g., $3.57\%$ testing error on CIFAR-$10$, $19.00\%$ on CIFAR-$100$, $1.51\%$ on SVHN).

##### Abstract (translated by Google)
通过堆积残差块序列构建的深度残差网络易于训练，因为身份映射跳过残余分支，从而改善信息流。为了进一步降低训练难度，我们提出了一个简单的网络体系结构，深度融合运行的神经网络。新颖之处在于模块化构建块，合并运行块，它通过合并运行映射并行组合残余分支：平均这些残余分支（合并）的输入，并将平均值加到每个残余分支分别作为后续残余分支（Run）的输入。我们证明合并运行映射是一个线性幂等函数，其中变换矩阵是幂等的，从而改善信息流，使得训练变得容易。与残余网络相比，我们的网络具有令人信服的优势：它们包含更短的路径，并且宽度，即通道数量增加。我们评估标准识别任务的性能。我们的方法通过可比较的设置证明了ResNets的持续改进，并且获得了有竞争力的结果（例如，在CIFAR上的$ 3.57 \％$测试错误$ 10 $，在CIFAR上$ 19 $ \ $ $ $ $ $，在SVHN上$ 1.51 \％$）。

##### URL
[https://arxiv.org/abs/1611.07718](https://arxiv.org/abs/1611.07718)

##### PDF
[https://arxiv.org/pdf/1611.07718](https://arxiv.org/pdf/1611.07718)

