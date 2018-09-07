---
layout: post
title: "Travel Speed Prediction with a Hierarchical Convolutional Neural Network and Long Short-Term Memory Model Framework"
date: 2018-09-06 09:00:57
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Prediction
author: Wei Wang (1), Xucheng Li (2) ((1) Akins (SNC-Lavalin), UK, (2) Shenzhen Urban Transport Planning Center Co. Ltd, China)
mathjax: true
---

* content
{:toc}

##### Abstract
Advanced travel information and warning, if provided accurately, can help road users avoid traffic congestion through dynamic route planning and behavior change. It also enables traffic control centres mitigate the impact of congestion by activating Intelligent Transport System (ITS) proactively. Deep learning has become increasingly popular in recent years, following a surge of innovative GPU technology, high-resolution, big datasets and thriving machine learning algorithms. However, there are few examples exploiting this emerging technology to develop applications for traffic prediction. This is largely due to the difficulty in capturing random, seasonal, non-linear, and spatio-temporal correlated nature of traffic data. In this paper, we propose a data-driven modelling approach with a novel hierarchical D-CLSTM-t deep learning model for short-term traffic speed prediction, a framework combined with convolutional neural network (CNN) and long short-term memory (LSTM) models. A deep CNN model is employed to learn the spatio-temporal traffic patterns of the input graphs, which are then fed into a deep LSTM model for sequence learning. To capture traffic seasonal variations, time of the day and day of the week indicators are fused with trained features. The model is trained end-to-end to predict travel speed in 15 to 90 minutes in the future. We compare the model performance against other baseline models including CNN, LGBM, LSTM, and traditional speed-flow curves. Experiment results show that the D-CLSTM-t outperforms other models considerably. Model tests show that speed upstream also responds sensibly to a sudden accident occurring downstream. Our D-CLSTM-t model framework is also highly scalable for future extension such as for network-wide traffic prediction, which can also be improved by including additional features such as weather, long term seasonality and accident information.

##### Abstract (translated by Google)
如果准确提供高级旅行信息和警告，可以帮助道路使用者通过动态路线规划和行为改变来避免交通拥堵。它还使交通控制中心能够通过主动激活智能交通系统（ITS）来减轻拥堵的影响。随着创新的GPU技术，高分辨率，大数据集和蓬勃发展的机器学习算法的激增，深度学习近年来变得越来越流行。但是，很少有利用这种新兴技术开发流量预测应用的例子。这主要是由于难以捕获交通数据的随机，季节性，非线性和时空相关性质。在本文中，我们提出了一种数据驱动建模方法，该方法具有用于短期交通速度预测的新型分层D-CLSTM-t深度学习模型，与卷积神经网络（CNN）和长期短期记忆相结合的框架（LSTM） ） 楷模。采用深度CNN模型来学习输入图的时空交通模式，然后将其输入深度LSTM模型以进行序列学习。为了捕获交通季节性变化，一天中的时间和星期几指标与训练有素的特征融合在一起。该模型经过端到端的培训，可预测未来15至90分钟的行驶速度。我们将模型性能与其他基线模型进行比较，包括CNN，LGBM，LSTM和传统的速度 - 流量曲线。实验结果表明，D-CLSTM-t在很大程度上优于其他模型。模型试验表明，上游速度对下游发生的突发事故也有明显的响应。我们的D-CLSTM-t模型框架对于未来扩展也具有高度可扩展性，例如用于网络范围的流量预测，还可以通过包括诸如天气，长期季节性和事故信息等附加功能来改进。

##### URL
[https://arxiv.org/abs/1809.01887](https://arxiv.org/abs/1809.01887)

##### PDF
[https://arxiv.org/pdf/1809.01887](https://arxiv.org/pdf/1809.01887)

