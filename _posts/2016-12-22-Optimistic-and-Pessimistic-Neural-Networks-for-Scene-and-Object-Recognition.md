---
layout: post
title: "Optimistic and Pessimistic Neural Networks for Scene and Object Recognition"
date: 2016-12-22 12:25:35
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction Detection Recognition
author: Rene Grzeszick, Sebastian Sudholt, Gernot A. Fink
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper the application of uncertainty modeling to convolutional neural networks is evaluated. A novel method for adjusting the network's predictions based on uncertainty information is introduced. This allows the network to be either optimistic or pessimistic in its prediction scores. The proposed method builds on the idea of applying dropout at test time and sampling a predictive mean and variance from the network's output. Besides the methodological aspects, implementation details allowing for a fast evaluation are presented. Furthermore, a multilabel network architecture is introduced that strongly benefits from the presented approach. In the evaluation it will be shown that modeling uncertainty allows for improving the performance of a given model purely at test time without any further training steps. The evaluation considers several applications in the field of computer vision, including object classification and detection as well as scene attribute recognition.

##### Abstract (translated by Google)
本文对不确定性建模技术在卷积神经网络中的应用进行了评估。介绍了一种基于不确定性信息的网络预测调整方法。这使得网络的预测分数可以是乐观的或悲观的。所提出的方法基于在测试时间应用丢弃并从网络输出中取样预测均值和方差的思想。除了方法学方面外，还介绍了允许快速评估的实施细节。此外，引入了多标签网络体系结构，从所提出的方法中受益良多。在评估中，将显示建模不确定性允许纯粹在测试时间改进给定模型的性能，而无需任何进一步的训练步骤。评估考虑了在计算机视觉领域的几个应用，包括对象分类和检测以及场景属性识别。

##### URL
[https://arxiv.org/abs/1609.07982](https://arxiv.org/abs/1609.07982)

##### PDF
[https://arxiv.org/pdf/1609.07982](https://arxiv.org/pdf/1609.07982)

