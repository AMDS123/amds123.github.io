---
layout: post
title: "Median-Based Generation of Synthetic Speech Durations using a Non-Parametric Approach"
date: 2016-11-11 13:24:44
categories: arXiv_CL
tags: arXiv_CL Prediction
author: Srikanth Ronanki, Oliver Watts, Simon King, Gustav Eje Henter
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new approach to duration modelling for statistical parametric speech synthesis in which a recurrent statistical model is trained to output a phone transition probability at each timestep (acoustic frame). Unlike conventional approaches to duration modelling -- which assume that duration distributions have a particular form (e.g., a Gaussian) and use the mean of that distribution for synthesis -- our approach can in principle model any distribution supported on the non-negative integers. Generation from this model can be performed in many ways; here we consider output generation based on the median predicted duration. The median is more typical (more probable) than the conventional mean duration, is robust to training-data irregularities, and enables incremental generation. Furthermore, a frame-level approach to duration prediction is consistent with a longer-term goal of modelling durations and acoustic features together. Results indicate that the proposed method is competitive with baseline approaches in approximating the median duration of held-out natural speech.

##### Abstract (translated by Google)
本文提出了统计参数语音合成持续时间建模的新方法，其中经常性统计模型被训练以在每个时间步（声音帧）输出电话转换概率。与传统的持续时间建模方法不同，后者假定持续时间分布具有特定的形式（例如高斯分布），并使​​用该分布的平均值进行综合 - 我们的方法原则上可模拟任何非负整数支持的分布。从这个模型生成可以用很多方法来执行;这里我们考虑基于中位数预测持续时间的输出生成。中位数比传统的平均持续时间更为典型（更可能），对于训练数据的不规则性是有力的，并且可以实现增量式生成。此外，持续时间预测的框架级方法与将持续时间和声学特征一起建模的较长期目标是一致的。结果表明，所提出的方法在逼近持续自然语音的中值持续时间方面与基线方法具有竞争性。

##### URL
[https://arxiv.org/abs/1608.06134](https://arxiv.org/abs/1608.06134)

##### PDF
[https://arxiv.org/pdf/1608.06134](https://arxiv.org/pdf/1608.06134)

