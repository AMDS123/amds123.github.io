---
layout: post
title: "Mining Object Parts from CNNs via Active Question-Answering"
date: 2017-04-11 07:27:33
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification
author: Quanshi Zhang, Ruiming Cao, Ying Nian Wu, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Given a convolutional neural network (CNN) that is pre-trained for object classification, this paper proposes to use active question-answering to semanticize neural patterns in conv-layers of the CNN and mine part concepts. For each part concept, we mine neural patterns in the pre-trained CNN, which are related to the target part, and use these patterns to construct an And-Or graph (AOG) to represent a four-layer semantic hierarchy of the part. As an interpretable model, the AOG associates different CNN units with different explicit object parts. We use an active human-computer communication to incrementally grow such an AOG on the pre-trained CNN as follows. We allow the computer to actively identify objects, whose neural patterns cannot be explained by the current AOG. Then, the computer asks human about the unexplained objects, and uses the answers to automatically discover certain CNN patterns corresponding to the missing knowledge. We incrementally grow the AOG to encode new knowledge discovered during the active-learning process. In experiments, our method exhibits high learning efficiency. Our method uses about 1/6-1/3 of the part annotations for training, but achieves similar or better part-localization performance than fast-RCNN methods.

##### Abstract (translated by Google)
给定一个针对对象分类进行预训练的卷积神经网络（CNN），本文提出采用主动的问答方式将CNN的卷积层和矿区概念中的神经模式语义化。对于每个部分的概念，我们在预先训练的CNN中挖掘与目标部分相关的神经模式，并使用这些模式构造一个And-Or图（AOG）来表示该部分的四层语义层次结构。作为可解释的模型，AOG将不同的CNN单元与不同的显式对象部分关联起来。我们使用一个主动的人机交流来在预训练的CNN上递增地增长这样一个AOG，如下所示。我们允许计算机主动识别目前AOG无法解释的神经模式。然后，计算机向人类询问不明原因的对象，并使用答案自动发现与缺失的知识对应的某些CNN模式。我们逐渐增加AOG，以编码主动学习过程中发现的新知识。在实验中，我们的方法展现出高学习效率。我们的方法使用约1 / 6-1 / 3的部分注释进行训练，但是实现了类似或更好的部分定位性能比快速RCNN方法。

##### URL
[https://arxiv.org/abs/1704.03173](https://arxiv.org/abs/1704.03173)

##### PDF
[https://arxiv.org/pdf/1704.03173](https://arxiv.org/pdf/1704.03173)

