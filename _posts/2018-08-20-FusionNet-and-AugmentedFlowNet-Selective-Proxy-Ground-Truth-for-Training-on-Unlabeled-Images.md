---
layout: post
title: "FusionNet and AugmentedFlowNet: Selective Proxy Ground Truth for Training on Unlabeled Images"
date: 2018-08-20 11:18:06
categories: arXiv_CV
tags: arXiv_CV CNN
author: Osama Makansi, Eddy Ilg, Thomas Brox
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that convolutional neural networks (CNNs) can be used to estimate optical flow with high quality and fast runtime. This makes them preferable for real-world applications. However, such networks require very large training datasets. Engineering the training data is difficult and/or laborious. This paper shows how to augment a network trained on an existing synthetic dataset with large amounts of additional unlabelled data. In particular, we introduce a selection mechanism to assemble from multiple estimates a joint optical flow field, which outperforms that of all input methods. The latter can be used as proxy-ground-truth to train a network on real-world data and to adapt it to specific domains of interest. Our experimental results show that the performance of networks improves considerably, both, in cross-domain and in domain-specific scenarios. As a consequence, we obtain state-of-the-art results on the KITTI benchmarks.

##### Abstract (translated by Google)
最近的工作表明，卷积神经网络（CNN）可用于估计高质量和快速运行时的光流。这使它们更适合实际应用。但是，这种网络需要非常大的训练数据集。设计训练数据是困难和/或费力的。本文介绍了如何使用大量额外的未标记数据来扩充在现有合成数据集上训练的网络。特别地，我们引入了一种选择机制，用于从多个估计中组合一个联合光流场，其优于所有输入方法。后者可以用作代理 - 地面实况，以在真实世界数据上训练网络并使其适应特定的感兴趣领域。我们的实验结果表明，在跨域和特定于域的场景中，网络性能都得到了显着提高。因此，我们在KITTI基准测试中获得了最先进的结果。

##### URL
[http://arxiv.org/abs/1808.06389](http://arxiv.org/abs/1808.06389)

##### PDF
[http://arxiv.org/pdf/1808.06389](http://arxiv.org/pdf/1808.06389)

