---
layout: post
title: "Analyzing and Mitigating the Impact of Permanent Faults on a Systolic Array Based Neural Network Accelerator"
date: 2018-02-11 19:51:35
categories: arXiv_CV
tags: arXiv_CV Optimization Classification
author: Jeff (Jun) Zhang, Tianyu Gu, Kanad Basu, Siddharth Garg
mathjax: true
---

* content
{:toc}

##### Abstract
Due to their growing popularity and computational cost, deep neural networks (DNNs) are being targeted for hardware acceleration. A popular architecture for DNN acceleration, adopted by the Google Tensor Processing Unit (TPU), utilizes a systolic array based matrix multiplication unit at its core. This paper deals with the design of fault-tolerant, systolic array based DNN accelerators for high defect rate technologies. To this end, we empirically show that the classification accuracy of a baseline TPU drops significantly even at extremely low fault rates (as low as $0.006\%$). We then propose two novel strategies, fault-aware pruning (FAP) and fault-aware pruning+retraining (FAP+T), that enable the TPU to operate at fault rates of up to $50\%$, with negligible drop in classification accuracy (as low as $0.1\%$) and no run-time performance overhead. The FAP+T does introduce a one-time retraining penalty per TPU chip before it is deployed, but we propose optimizations that reduce this one-time penalty to under 12 minutes. The penalty is then amortized over the entire lifetime of the TPU's operation.

##### Abstract (translated by Google)
由于其日益普及和计算成本，深度神经网络（DNN）正在成为硬件加速的目标。谷歌张量处理单元（TPU）采用的一种流行的DNN加速体系结构，其核心采用了基于收缩阵列的矩阵乘法单元。本文介绍了基于容错，脉动阵列的DNN加速器在高缺陷率技术中的设计。为此，我们凭经验证明即使在极低的故障率下（即低至0.006美元％），基线TPU的分类精度也会显着下降。然后，我们提出了两种新颖的策略，即故障感知修剪（FAP）和故障感知修剪+再训练（FAP + T），使TPU能够以高达50美元/美元的故障率运行，分类精度可以忽略不计（低至$ 0.1 \％$），并且没有运行时性能开销。在部署前，FAP + T在TPU芯片上引入了一次性再培训惩罚措施，但我们建议将这种一次性惩罚降低到12分钟以下的优化。然后罚款在TPU的整个生命周期内摊销。

##### URL
[http://arxiv.org/abs/1802.04657](http://arxiv.org/abs/1802.04657)

##### PDF
[http://arxiv.org/pdf/1802.04657](http://arxiv.org/pdf/1802.04657)

