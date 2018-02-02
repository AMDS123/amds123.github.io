---
layout: post
title: "Crowd Flow Prediction by Deep Spatio-Temporal Transfer Learning"
date: 2018-02-01 16:52:42
categories: arXiv_AI
tags: arXiv_AI Knowledge Transfer_Learning Deep_Learning Prediction
author: Leye Wang, Xu Geng, Xiaojuan Ma, Feng Liu, Qiang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Crowd flow prediction is a fundamental urban computing problem. Recently, deep learning has been successfully applied to solve this problem, but it relies on rich historical data. In reality, many cities may suffer from data scarcity issue when their targeted service or infrastructure is new. To overcome this issue, this paper proposes a novel deep spatio-temporal transfer learning framework, called RegionTrans, which can predict future crowd flow in a data-scarce (target) city by transferring knowledge from a data-rich (source) city. Leveraging social network check-ins, RegionTrans first links a region in the target city to certain regions in the source city, expecting that these inter-city region pairs will share similar crowd flow dynamics. Then, we propose a deep spatio-temporal neural network structure, in which a hidden layer is dedicated to keeping the region representation. A source city model is then trained on its rich historical data with this network structure. Finally, we propose a region-based cross-city transfer learning algorithm to learn the target city model from the source city model by minimizing the hidden representation discrepancy between the inter-city region pairs previously linked by check-ins. With experiments on real crowd flow, RegionTrans can outperform state-of-the-arts by reducing up to 10.7% prediction error.

##### Abstract (translated by Google)
人群流量预测是一个基本的城市计算问题。近年来，深度学习已经成功地应用于解决这个问题，但是依靠丰富的历史数据。事实上，许多城市的目标服务或基础设施是新的时候可能会遇到数据稀缺问题。为了克服这个问题，本文提出了一种新的深空时传递学习框架，称为RegionTrans，它可以通过从一个数据丰富（源）城市转移知识来预测数据稀缺（目标）城市未来的人群流动。利用社交网络检查，RegionTrans首先将目标城市的某个地区连接到源城市中的某些地区，期望这些城际地区对将共享相似的人群流动动态。然后，我们提出了一个深层的时空神经网络结构，其中一个隐藏层专门用于保持区域表示。然后用这个网络结构对源城市模型进行丰富的历史数据训练。最后，我们提出了一个基于区域的跨城市转移学习算法，通过最小化之前通过签入连接的城市间区域对之间的隐藏表示差异，从源城市模型中学习目标城市模型。通过对真实人群流量进行实验，RegionTrans可以减少高达10.7％的预测误差，从而超越现有技术水平。

##### URL
[http://arxiv.org/abs/1802.00386](http://arxiv.org/abs/1802.00386)

##### PDF
[http://arxiv.org/pdf/1802.00386](http://arxiv.org/pdf/1802.00386)

