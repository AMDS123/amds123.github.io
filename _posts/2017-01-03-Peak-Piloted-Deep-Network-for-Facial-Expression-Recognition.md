---
layout: post
title: "Peak-Piloted Deep Network for Facial Expression Recognition"
date: 2017-01-03 08:19:24
categories: arXiv_CV
tags: arXiv_CV Face Optimization Recognition Face_Recognition
author: Xiangyun Zhao, Xiaodan Liang, Luoqi Liu, Teng Li, Yugang Han, Nuno Vasconcelos, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Objective functions for training of deep networks for face-related recognition tasks, such as facial expression recognition (FER), usually consider each sample independently. In this work, we present a novel peak-piloted deep network (PPDN) that uses a sample with peak expression (easy sample) to supervise the intermediate feature responses for a sample of non-peak expression (hard sample) of the same type and from the same subject. The expression evolving process from non-peak expression to peak expression can thus be implicitly embedded in the network to achieve the invariance to expression intensities. A special purpose back-propagation procedure, peak gradient suppression (PGS), is proposed for network training. It drives the intermediate-layer feature responses of non-peak expression samples towards those of the corresponding peak expression samples, while avoiding the inverse. This avoids degrading the recognition capability for samples of peak expression due to interference from their non-peak expression counterparts. Extensive comparisons on two popular FER datasets, Oulu-CASIA and CK+, demonstrate the superiority of the PPDN over state-ofthe-art FER methods, as well as the advantages of both the network structure and the optimization strategy. Moreover, it is shown that PPDN is a general architecture, extensible to other tasks by proper definition of peak and non-peak samples. This is validated by experiments that show state-of-the-art performance on pose-invariant face recognition, using the Multi-PIE dataset.

##### Abstract (translated by Google)
面部相关识别任务（如面部表情识别（FER））的深度网络训练的目标函数通常独立地考虑每个样本。在这项工作中，我们提出了一个新的峰值先导深网络（PPDN），使用峰值表达样本（简单样本）来监督相同类型的非峰值表达（硬样本）样本的中间特征响应和来自同一主题。因此，从非峰值表达到峰值表达的表达演变过程可以隐含地嵌入网络中以实现表达强度的不变性。提出了一种特殊用途的反向传播过程峰值梯度抑制（PGS），用于网络训练。它将非峰值表达样本的中间层特征响应驱向相应峰值表达样本的中间层特征响应，同时避免相反的情况。这避免了由于来自非峰值表达对应物的干扰而降低了对峰值表达样品的识别能力。在两个流行的FER数据集，Oulu-CASIA和CK +上的广泛比较，证明了PPDN优于最先进的FER方法的优越性，以及网络结构和优化策略的优点。此外，它表明，PPDN是一个通用的架构，可扩展到其他任务通过适当定义的峰值和非峰值样本。这通过使用多PIE数据集显示姿态不变人脸识别的最新性能的实验来验证。

##### URL
[https://arxiv.org/abs/1607.06997](https://arxiv.org/abs/1607.06997)

##### PDF
[https://arxiv.org/pdf/1607.06997](https://arxiv.org/pdf/1607.06997)

