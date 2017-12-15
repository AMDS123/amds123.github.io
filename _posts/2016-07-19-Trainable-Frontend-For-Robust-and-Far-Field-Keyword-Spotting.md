---
layout: post
title: "Trainable Frontend For Robust and Far-Field Keyword Spotting"
date: 2016-07-19 17:17:58
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Inference Recognition
author: Yuxuan Wang, Pascal Getreuer, Thad Hughes, Richard F. Lyon, Rif A. Saurous
mathjax: true
---

* content
{:toc}

##### Abstract
Robust and far-field speech recognition is critical to enable true hands-free communication. In far-field conditions, signals are attenuated due to distance. To improve robustness to loudness variation, we introduce a novel frontend called per-channel energy normalization (PCEN). The key ingredient of PCEN is the use of an automatic gain control based dynamic compression to replace the widely used static (such as log or root) compression. We evaluate PCEN on the keyword spotting task. On our large rerecorded noisy and far-field eval sets, we show that PCEN significantly improves recognition performance. Furthermore, we model PCEN as neural network layers and optimize high-dimensional PCEN parameters jointly with the keyword spotting acoustic model. The trained PCEN frontend demonstrates significant further improvements without increasing model complexity or inference-time cost.

##### Abstract (translated by Google)
鲁棒性和远场语音识别对于实现真正的免提通信至关重要。在远场条件下，信号由于距离而衰减。为了提高对响度变化的鲁棒性，我们引入了一种称为每通道能量归一化（PCEN）的新型前端。 PCEN的关键部分是使用基于自动增益控制的动态压缩来代替广泛使用的静态（如日志或根）压缩。我们评估关键字spotting任务上的PCEN。在我们的大型重新记录嘈杂和远场eval集，我们表明，PCEN显着提高识别性能。此外，我们将PCEN建模为神经网络层，并与关键词点声模型一起优化高维PCEN参数。经过培训的PCEN前端在不增加模型复杂性或推理时间成本的前提下，可以进一步提高性能。

##### URL
[https://arxiv.org/abs/1607.05666](https://arxiv.org/abs/1607.05666)

##### PDF
[https://arxiv.org/pdf/1607.05666](https://arxiv.org/pdf/1607.05666)

