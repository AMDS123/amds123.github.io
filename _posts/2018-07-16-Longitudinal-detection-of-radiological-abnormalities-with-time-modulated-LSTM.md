---
layout: post
title: "Longitudinal detection of radiological abnormalities with time-modulated LSTM"
date: 2018-07-16 22:53:46
categories: arXiv_CV
tags: arXiv_CV CNN RNN Classification Detection Memory_Networks
author: Ruggiero Santeramo, Samuel Withey, Giovanni Montana
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have been successfully employed in recent years for the detection of radiological abnormalities in medical images such as plain x-rays. To date, most studies use CNNs on individual examinations in isolation and discard previously available clinical information. In this study we set out to explore whether Long-Short-Term-Memory networks (LSTMs) can be used to improve classification performance when modelling the entire sequence of radiographs that may be available for a given patient, including their reports. A limitation of traditional LSTMs, though, is that they implicitly assume equally-spaced observations, whereas the radiological exams are event-based, and therefore irregularly sampled. Using both a simulated dataset and a large-scale chest x-ray dataset, we demonstrate that a simple modification of the LSTM architecture, which explicitly takes into account the time lag between consecutive observations, can boost classification performance. Our empirical results demonstrate improved detection of commonly reported abnormalities on chest x-rays such as cardiomegaly, consolidation, pleural effusion and hiatus hernia.

##### Abstract (translated by Google)
近年来，卷积神经网络（CNN）已被成功用于检测医学图像（例如普通X射线）中的放射学异常。迄今为止，大多数研究单独使用CNN进行个别检查，并丢弃以前可用的临床信息。在这项研究中，我们开始探索是否可以使用长短期记忆网络（LSTM）来模拟给定患者可能获得的整个X光片序列，包括他们的报告，从而提高分类性能。然而，传统LSTM的局限性在于它们隐含地假设等距观测，而放射性检查是基于事件的，因此是不规则采样的。使用模拟数据集和大型胸部X射线数据集，我们证明了LSTM架构的简单修改，明确考虑了连续观察之间的时间滞后，可以提高分类性能。我们的实验结果表明，对心脏肿大，巩固，胸腔积液和裂孔疝等胸部X线异常的常见报告进行了改进检测。

##### URL
[http://arxiv.org/abs/1807.06144](http://arxiv.org/abs/1807.06144)

##### PDF
[http://arxiv.org/pdf/1807.06144](http://arxiv.org/pdf/1807.06144)

