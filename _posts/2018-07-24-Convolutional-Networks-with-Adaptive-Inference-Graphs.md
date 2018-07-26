---
layout: post
title: "Convolutional Networks with Adaptive Inference Graphs"
date: 2018-07-24 19:21:00
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Inference Classification
author: Andreas Veit, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
Do convolutional networks really need a fixed feed-forward structure? What if, after identifying the high-level concept of an image, a network could move directly to a layer that can distinguish fine-grained differences? Currently, a network would first need to execute sometimes hundreds of intermediate layers that specialize in unrelated aspects. Ideally, the more a network already knows about an image, the better it should be at deciding which layer to compute next. In this work, we propose convolutional networks with adaptive inference graphs (ConvNet-AIG) that adaptively define their network topology conditioned on the input image. Following a high-level structure similar to residual networks (ResNets), ConvNet-AIG decides for each input image on the fly which layers are needed. In experiments on ImageNet we show that ConvNet-AIG learns distinct inference graphs for different categories. Both ConvNet-AIG with 50 and 101 layers outperform their ResNet counterpart, while using 20% and 33% less computations respectively. By grouping parameters into layers for related classes and only executing relevant layers, ConvNet-AIG improves both efficiency and overall classification quality. Lastly, we also study the effect of adaptive inference graphs on the susceptibility towards adversarial examples. We observe that ConvNet-AIG shows a higher robustness than ResNets, complementing other known defense mechanisms.

##### Abstract (translated by Google)
卷积网络真的需要固定的前馈结构吗？如果在确定图像的高级概念之后，网络可以直接移动到可以区分细粒度差异的层，那该怎么办？目前，网络首先需要执行数百个专门处理无关方面的中间层。理想情况下，网络已经越了解图像，就越能够决定下一个要计算的图层。在这项工作中，我们提出了具有自适应推理图（ConvNet-AIG）的卷积网络，该网络根据输入图像自适应地定义其网络拓扑。遵循类似于剩余网络（ResNets）的高级结构，ConvNet-AIG在运行中决定每个输入图像需要哪些层。在ImageNet上的实验中，我们展示了ConvNet-AIG为不同的类别学习了不同的推理图。具有50和101层的ConvNet-AIG均优于其ResNet对应物，同时分别使用20％和33％的计算。通过将参数分组为相关类的层并仅执行相关层，ConvNet-AIG提高了效率和整体分类质量。最后，我们还研究了自适应推理图对对抗性例子的敏感性的影响。我们观察到ConvNet-AIG显示出比ResNets更高的鲁棒性，补充了其他已知的防御机制。

##### URL
[http://arxiv.org/abs/1711.11503](http://arxiv.org/abs/1711.11503)

##### PDF
[http://arxiv.org/pdf/1711.11503](http://arxiv.org/pdf/1711.11503)

