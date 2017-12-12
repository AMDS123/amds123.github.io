---
layout: post
title: "Tags2Parts: Discovering Semantic Regions from Shape Tags"
date: 2017-12-09 11:26:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Prediction
author: Sanjeev Muralikrishnan, Vladimir G. Kim, Siddhartha Chaudhuri
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for discovering shape regions that strongly correlate with user-prescribed tags. For example, given a collection of chairs tagged as either "has armrest" or "lacks armrest", our system correctly highlights the armrest regions as the main distinctive parts between the two chair types. To obtain point-wise predictions from shape-wise tags we develop a novel neural network architecture that is trained with tag classification loss, but is designed to rely on segmentation to predict the tag. Our network is inspired by U-Net, but we replicate shallow U structures several times with new skip connections and pooling layers, and call the resulting architecture "WU-Net". We test our method on segmentation benchmarks and show that even with weak supervision of whole shape tags, our method can infer meaningful semantic regions, without ever observing shape segmentations. Further, once trained, the model can process shapes for which the tag is entirely unknown. As a bonus, our architecture is directly operational under full supervision and performs strongly on standard benchmarks. We validate our method through experiments with many variant architectures and prior baselines, and demonstrate several applications.

##### Abstract (translated by Google)
我们提出了一种新的方法来发现与用户指定的标签密切相关的形状区域。例如，如果椅子标记为“有扶手”或“没有扶手”，则我们的系统将扶手区域正确地突出为两种椅子类型之间的主要区别部分。为了从形状标签中获得逐点预测，我们开发了一种新的神经网络结构，该结构经过标签分类损失训练，但是被设计为依靠分割来预测标签。我们的网络受到U-Net的启发，但我们用新的跳转连接和汇聚层多次复制浅U结构，并调用由此产生的架构“WU-Net”。我们测试我们的分割基准的方法，并表明，即使对整个形状标签的弱监督，我们的方法可以推断有意义的语义区域，而无需观察形状分割。此外，一旦训练完毕，模型可以处理标签完全未知的形状。作为奖励，我们的架构可以在全面监督下直接运行，并在标准基准测试中表现强劲。我们通过对许多变体结构和先前的基线进行实验来验证我们的方法，并演示了几种应用。

##### URL
[http://arxiv.org/abs/1708.06673](http://arxiv.org/abs/1708.06673)

##### PDF
[http://arxiv.org/pdf/1708.06673](http://arxiv.org/pdf/1708.06673)

