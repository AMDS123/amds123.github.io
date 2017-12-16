---
layout: post
title: "Few-Shot Object Recognition from Machine-Labeled Web Images"
date: 2016-12-19 12:25:36
categories: arXiv_CV
tags: arXiv_CV Attention Embedding CNN RNN Prediction Recognition
author: Zhongwen Xu, Linchao Zhu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
With the tremendous advances of Convolutional Neural Networks (ConvNets) on object recognition, we can now obtain reliable enough machine-labeled annotations easily by predictions from off-the-shelf ConvNets. In this work, we present an abstraction memory based framework for few-shot learning, building upon machine-labeled image annotations. Our method takes some large-scale machine-annotated datasets (e.g., OpenImages) as an external memory bank. In the external memory bank, the information is stored in the memory slots with the form of key-value, where image feature is regarded as key and label embedding serves as value. When queried by the few-shot examples, our model selects visually similar data from the external memory bank, and writes the useful information obtained from related external data into another memory bank, i.e., abstraction memory. Long Short-Term Memory (LSTM) controllers and attention mechanisms are utilized to guarantee the data written to the abstraction memory is correlated to the query example. The abstraction memory concentrates information from the external memory bank, so that it makes the few-shot recognition effective. In the experiments, we firstly confirm that our model can learn to conduct few-shot object recognition on clean human-labeled data from ImageNet dataset. Then, we demonstrate that with our model, machine-labeled image annotations are very effective and abundant resources to perform object recognition on novel categories. Experimental results show that our proposed model with machine-labeled annotations achieves great performance, only with a gap of 1% between of the one with human-labeled annotations.

##### Abstract (translated by Google)
随着卷积神经网络（ConvNets）在物体识别方面的巨大进步，我们现在可以通过现成的ConvNets的预测，轻松获得足够可靠的机器标注的注释。在这项工作中，我们提出了一个基于抽象记忆的框架，用于少量学习，建立在机器标记的图像注释上。我们的方法将一些大型机器注释的数据集（例如，OpenImages）作为外部存储库。在外部存储库中，信息以键值的形式存储在内存槽中，其中图像特征被视为关键字，标签嵌入作为值。当通过少数例子查询时，我们的模型从外部存储体中选择视觉上相似的数据，并将从相关外部数据获得的有用信息写入另一个存储体，即抽象存储器。使用长期短期记忆（LSTM）控制器和注意机制来保证写入抽象存储器的数据与查询示例相关。抽象存储器集中来自外部存储库的信息，使得少数识别有效。在实验中，我们首先证实了我们的模型可以从ImageNet数据集中学习对干净的人标记数据进行少量的目标识别。然后，我们证明，在我们的模型中，机器标记的图像注释是非常有效和丰富的资源来执行对新类别的对象识别。实验结果表明，我们提出的带有机器标注的注释模型取得了很好的性能，与人标注释之间的差距仅为1％。

##### URL
[https://arxiv.org/abs/1612.06152](https://arxiv.org/abs/1612.06152)

##### PDF
[https://arxiv.org/pdf/1612.06152](https://arxiv.org/pdf/1612.06152)

