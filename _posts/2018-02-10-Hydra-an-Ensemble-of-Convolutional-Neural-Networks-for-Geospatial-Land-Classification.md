---
layout: post
title: "Hydra: an Ensemble of Convolutional Neural Networks for Geospatial Land Classification"
date: 2018-02-10 04:16:36
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification
author: Rodrigo Minetto, Mauricio Pamplona Segundo, Sudeep Sarkar
mathjax: true
---

* content
{:toc}

##### Abstract
We describe in this paper Hydra, an ensemble of convolutional neural networks (CNN) for geospatial land classification. The idea behind Hydra is to create an initial CNN that is coarsely optimized but provides a good starting pointing for further optimization, which will serve as the Hydra's body. Then, the obtained weights are fine tuned multiple times to form an ensemble of CNNs that represent the Hydra's heads. By doing so, we were able to reduce the training time while maintaining the classification performance of the ensemble. We created ensembles using two state-of-the-art CNN architectures, ResNet and DenseNet, to participate in the Functional Map of the World challenge. With this approach, we finished the competition in third place. We also applied the proposed framework to the NWPU-RESISC45 database and achieved the best reported performance so far. Code and CNN models are available at https://github.com/maups/hydra-fmow

##### Abstract (translated by Google)
我们在本文中描述Hydra，一种用于地理空间土地分类的卷积神经网络（CNN）集合。 Hydra背后的想法是创建一个粗略优化的初始CNN，但为进一步优化提供了一个良好的起点，它将作为Hydra的身体。然后，所获得的权重被多次微调以形成代表Hydra头部的CNN的集合。通过这样做，我们能够减少训练时间，同时保持整体的分类性能。我们使用两种最先进的CNN体​​系结构ResNet和DenseNet创建了合奏，以参与世界功能地图挑战。采用这种方法，我们完成了第三名的比赛。我们还将所提议的框架应用于NWPU-RESISC45数据库，并且迄今为止获得了最佳的报告表现。代码和CNN模型可在https://github.com/maups/hydra-fmow获得

##### URL
[http://arxiv.org/abs/1802.03518](http://arxiv.org/abs/1802.03518)

##### PDF
[http://arxiv.org/pdf/1802.03518](http://arxiv.org/pdf/1802.03518)

