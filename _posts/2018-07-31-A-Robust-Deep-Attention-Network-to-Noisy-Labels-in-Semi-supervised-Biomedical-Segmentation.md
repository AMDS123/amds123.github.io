---
layout: post
title: "A Robust Deep Attention Network to Noisy Labels in Semi-supervised Biomedical Segmentation"
date: 2018-07-31 09:34:16
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Attention
author: Shaobo Min, Xuejin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Learning-based methods suffer from limited clean annotations, especially for biomedical segmentation. For example, the noisy labels make model confused and the limited labels lead to an inadequate training, which are usually concomitant. In this paper, we propose a deep attention networks (DAN) that is more robust to noisy labels by eliminating the bad gradients caused by noisy labels, using attention modules. Especially, the strategy of multi-stage filtering is applied, because clear elimination in a certain layer is impossible. As the prior knowledge of noise distribution is usually unavailable, a two-stream network is developed to provide information from each other for attention modules to mine potential distribution of noisy gradients. The intuition is that a discussion of two students may find out mistakes taught by teacher. And we further analyse the infection processing of noisy labels and design three attention modules, according to different disturbance of noisy labels in different layers. Furthermore, a hierarchical distillation is developed to provide more reliable pseudo labels from unlabeld data, which further boosts the DAN. Combining our DAN and hierarchical distillation can significantly improve a model performance with deficient clean annotations. The experiments on both HVSMR 2016 and BRATS 2015 benchmarks demonstrate the effectiveness of our method.

##### Abstract (translated by Google)
基于学习的方法受到有限的清洁注释的影响，特别是对于生物医学分割。例如，嘈杂的标签使模型混淆，有限的标签导致训练不足，这通常是伴随的。在本文中，我们提出了一种深度注意网络（DAN），它通过使用注意模块消除由噪声标签引起的不良梯度，对噪声标签更加鲁棒。特别是，应用了多级滤波的策略，因为不可能在某一层中清楚地消除。由于噪声分布的先验知识通常不可用，因此开发了双流网络以相互提供关注模块的信息以挖掘噪声梯度的潜在分布。直觉是对两个学生的讨论可能会发现老师教的错误。并根据不同层次噪声标签的不同干扰，进一步分析噪声标签的感染处理，设计三个注意模块。此外，开发了分层蒸馏以从未标记数据提供更可靠的伪标记，这进一步增强了DAN。结合我们的DAN和分级蒸馏可以显着改善模型性能，并且缺少清洁注释。 HVSMR 2016和BRATS 2015基准测试的实验证明了我们的方法的有效性。

##### URL
[http://arxiv.org/abs/1807.11719](http://arxiv.org/abs/1807.11719)

##### PDF
[http://arxiv.org/pdf/1807.11719](http://arxiv.org/pdf/1807.11719)

