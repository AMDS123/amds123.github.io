---
layout: post
title: "Improving Adversarial Discriminative Domain Adaptation"
date: 2018-09-10 22:56:55
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Deep_Learning Recognition
author: Aaron Chadha, Yiannis Andreopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial discriminative domain adaptation (ADDA) is an efficient framework for unsupervised domain adaptation, where the source and target domains are assumed to have the same classes, but no labels are available for the target domain. While ADDA has already achieved significant training efficiency and competitive accuracy in comparison to generative adversarial networks, we investigate whether we can allow for further improvements in its convergence properties by incorporating source label knowledge during target domain training. To achieve this, our approach first modifies the discriminator output to jointly predict the source labels and distinguish inputs from the target domain. We then leverage on the various source/target and encoder/discriminator distribution combinations to propose two loss functions for adversarial training of the target encoder. Our final design minimizes the maximum mean discrepancy between source encoder and target discriminator distributions, which ties together adversarial and discrepancy-based loss functions that are frequently considered independently in recent deep learning domain adaptation methods. Beyond validating our framework on standard datasets like MNIST, MNIST-M, USPS and SVHN, we introduce and evaluate on a neuromorphic vision sensing (NVS) sign language recognition dataset, where the source domain constitutes emulated neuromorphic spike events converted from APS video and the target domain is experimental spike events from an NVS camera. Our results on all datasets show that our proposal is both simple and efficient, as it competes or outperforms the state-of-the-art in unsupervised domain adaptation.

##### Abstract (translated by Google)
对抗性判别域适应（ADDA）是无监督域适应的有效框架，其中假定源域和目标域具有相同的类，但是没有可用于目标域的标记。虽然与生成性对抗网络相比，ADDA已经实现了显着的培训效率和竞争准确性，但我们通过在目标域培训期间纳入源标签知识来研究是否可以允许进一步改善其收敛性质。为实现此目的，我们的方法首先修改鉴别器输出以联合预测源标签并区分输入与目标域。然后，我们利用各种源/目标和编码器/鉴别器分布组合来为目标编码器的对抗训练提出两个损失函数。我们的最终设计最小化了源编码器和目标鉴别器分布之间的最大平均差异，这种差异将基于对抗和基于差异的损失函数联系在一起，这些函数在最近的深度学习域自适应方法中经常被独立考虑。除了在MNIST，MNIST-M，USPS和SVHN等标准数据集上验证我们的框架之外，我们还介绍并评估神经形态视觉传感（NVS）手语识别数据集，其中源域构成从APS视频转换的模拟神经形态尖峰事件目标域是来自NVS相机的实验性尖峰事件。我们对所有数据集的结果表明，我们的提议既简单又有效，因为它在无监督的域适应中竞争或优于最先进的技术。

##### URL
[http://arxiv.org/abs/1809.03625](http://arxiv.org/abs/1809.03625)

##### PDF
[http://arxiv.org/pdf/1809.03625](http://arxiv.org/pdf/1809.03625)

