---
layout: post
title: "Image Captioning with Deep Bidirectional LSTMs"
date: 2016-07-20 14:19:37
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Caption CNN RNN Detection
author: Cheng Wang, Haojin Yang, Christian Bartz, Christoph Meinel
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents an end-to-end trainable deep bidirectional LSTM (Long-Short Term Memory) model for image captioning. Our model builds on a deep convolutional neural network (CNN) and two separate LSTM networks. It is capable of learning long term visual-language interactions by making use of history and future context information at high level semantic space. Two novel deep bidirectional variant models, in which we increase the depth of nonlinearity transition in different way, are proposed to learn hierarchical visual-language embeddings. Data augmentation techniques such as multi-crop, multi-scale and vertical mirror are proposed to prevent overfitting in training deep models. We visualize the evolution of bidirectional LSTM internal states over time and qualitatively analyze how our models "translate" image to sentence. Our proposed models are evaluated on caption generation and image-sentence retrieval tasks with three benchmark datasets: Flickr8K, Flickr30K and MSCOCO datasets. We demonstrate that bidirectional LSTM models achieve highly competitive performance to the state-of-the-art results on caption generation even without integrating additional mechanism (e.g. object detection, attention model etc.) and significantly outperform recent methods on retrieval task.

##### Abstract (translated by Google)
这项工作提出了一个端到端的可训练深度双向LSTM（长 - 短期记忆）模型的图像字幕。我们的模型建立在深度卷积神经网络（CNN）和两个独立的LSTM网络上。它能够通过在高层次的语义空间中利用历史和未来的上下文信息来学习长期的视觉语言交互。提出了两种新的深度双向变体模型，其中我们增加了不同深度的非线性转换，以学习分层视觉语言嵌入。为了防止训练深度模型中的过拟合，提出了数据增强技术，如多视角，多尺度和垂直镜像。我们可视化双向LSTM内部状态随时间的演变，并定性分析我们的模型如何“翻译”图像到句子。我们提出的模型评估字幕生成和图像句子检索任务与三个基准数据集：Flickr8K，Flickr30K和MSCOCO数据集。我们证明，即使没有集成附加机制（例如对象检测，注意模型等），双向LSTM模型也实现了对于字幕生成的最新结果的高度竞争性能，并且在检索任务方面明显胜过最近的方法。

##### URL
[https://arxiv.org/abs/1604.00790](https://arxiv.org/abs/1604.00790)

