---
layout: post
title: "Feedback Networks"
date: 2017-08-20 07:15:55
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Amir R. Zamir, Te-Lin Wu, Lin Sun, William Shen, Jitendra Malik, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, the most successful learning models in computer vision are based on learning successive representations followed by a decision layer. This is usually actualized through feedforward multilayer neural networks, e.g. ConvNets, where each layer forms one of such successive representations. However, an alternative that can achieve the same goal is a feedback based approach in which the representation is formed in an iterative manner based on a feedback received from previous iteration's output. We establish that a feedback based approach has several fundamental advantages over feedforward: it enables making early predictions at the query time, its output naturally conforms to a hierarchical structure in the label space (e.g. a taxonomy), and it provides a new basis for Curriculum Learning. We observe that feedback networks develop a considerably different representation compared to feedforward counterparts, in line with the aforementioned advantages. We put forth a general feedback based learning architecture with the endpoint results on par or better than existing feedforward networks with the addition of the above advantages. We also investigate several mechanisms in feedback architectures (e.g. skip connections in time) and design choices (e.g. feedback length). We hope this study offers new perspectives in quest for more natural and practical learning models.

##### Abstract (translated by Google)
目前，计算机视觉领域最成功的学习模式是基于学习连续的表示，然后是决策层。这通常通过前馈多层神经网络实现，例如， ConvNets，其中每一层形成这样的连续表示之一。然而，可以实现相同目标的替代方案是基于反馈的方法，其中基于从先前迭代的输出接收到的反馈以迭代方式形成表示。我们建立了一个基于反馈的方法，与前馈相比有几个基本的优点：它能够在查询时进行早期预测，其输出自然符合标签空间中的分层结构（例如分类），为课程提供了新的基础学习。我们观察到，反馈网络与前馈对象相比，开发了一个相当不同的表示，符合上述优点。我们提出了一个基于总体反馈的学习体系结构，其终点结果与现有的前馈网络相比甚至更好，并增加了上述优点。我们还研究了反馈体系结构中的几种机制（例如跳过连接）和设计选择（例如反馈长度）。我们希望这项研究提供了新的视角，寻求更自然和实用的学习模式。

##### URL
[https://arxiv.org/abs/1612.09508](https://arxiv.org/abs/1612.09508)

##### PDF
[https://arxiv.org/pdf/1612.09508](https://arxiv.org/pdf/1612.09508)

