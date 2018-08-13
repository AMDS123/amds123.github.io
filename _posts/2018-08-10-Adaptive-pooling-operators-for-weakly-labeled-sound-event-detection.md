---
layout: post
title: "Adaptive pooling operators for weakly labeled sound event detection"
date: 2018-08-10 16:35:17
categories: arXiv_SD
tags: arXiv_SD CNN Prediction Detection
author: Brian McFee, Justin Salamon, Juan Pablo Bello
mathjax: true
---

* content
{:toc}

##### Abstract
Sound event detection (SED) methods are tasked with labeling segments of audio recordings by the presence of active sound sources. SED is typically posed as a supervised machine learning problem, requiring strong annotations for the presence or absence of each sound source at every time instant within the recording. However, strong annotations of this type are both labor- and cost-intensive for human annotators to produce, which limits the practical scalability of SED methods. 
 In this work, we treat SED as a multiple instance learning (MIL) problem, where training labels are static over a short excerpt, indicating the presence or absence of sound sources but not their temporal locality. The models, however, must still produce temporally dynamic predictions, which must be aggregated (pooled) when comparing against static labels during training. To facilitate this aggregation, we develop a family of adaptive pooling operators---referred to as auto-pool---which smoothly interpolate between common pooling operators, such as min-, max-, or average-pooling, and automatically adapt to the characteristics of the sound sources in question. We evaluate the proposed pooling operators on three datasets, and demonstrate that in each case, the proposed methods outperform non-adaptive pooling operators for static prediction, and nearly match the performance of models trained with strong, dynamic annotations. The proposed method is evaluated in conjunction with convolutional neural networks, but can be readily applied to any differentiable model for time-series label prediction.

##### Abstract (translated by Google)
声音事件检测（SED）方法的任务是通过存在有源声源来标记音频记录的片段。 SED通常被认为是受监督的机器学习问题，在记录中的每个时刻需要对每个声源的存在或不存在进行强注释。然而，这种类型的强注释对于人类注释者来说都是劳动力和成本密集型的​​，这限制了SED方法的实际可扩展性。
 在这项工作中，我们将SED视为多实例学习（MIL）问题，其中训练标签在短的摘录中是静态的，指示声源的存在或不存在，而不是它们的时间局部性。但是，模型仍然必须产生时间上的动态预测，在训练期间与静态标签进行比较时必须进行汇总（汇集）。为了促进这种聚合，我们开发了一系列自适应池操作符（称为自动池），它在公共池操作符之间平滑插值，例如最小，最大或平均池，并自动适应有问题的声源的特征。我们在三个数据集上评估建议的池操作符，并证明在每种情况下，所提出的方法优于非自适应池操作符以进行静态预测，并且几乎匹配使用强大动态注释训练的模型的性能。所提出的方法与卷积神经网络一起评估，但是可以容易地应用于用于时间序列标签预测的任何可微分模型。

##### URL
[http://arxiv.org/abs/1804.10070](http://arxiv.org/abs/1804.10070)

##### PDF
[http://arxiv.org/pdf/1804.10070](http://arxiv.org/pdf/1804.10070)

