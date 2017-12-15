---
layout: post
title: "Sequence Prediction with Neural Segmental Models"
date: 2017-09-12 14:25:43
categories: arXiv_CL
tags: arXiv_CL Inference Classification Prediction
author: Hao Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Segments that span contiguous parts of inputs, such as phonemes in speech, named entities in sentences, actions in videos, occur frequently in sequence prediction problems. Segmental models, a class of models that explicitly hypothesizes segments, have allowed the exploration of rich segment features for sequence prediction. However, segmental models suffer from slow decoding, hampering the use of computationally expensive features. In this thesis, we introduce discriminative segmental cascades, a multi-pass inference framework that allows us to improve accuracy by adding higher-order features and neural segmental features while maintaining efficiency. We also show that instead of including more features to obtain better accuracy, segmental cascades can be used to speed up training and decoding. Segmental models, similarly to conventional speech recognizers, are typically trained in multiple stages. In the first stage, a frame classifier is trained with manual alignments, and then in the second stage, segmental models are trained with manual alignments and the out- puts of the frame classifier. However, obtaining manual alignments are time-consuming and expensive. We explore end-to-end training for segmental models with various loss functions, and show how end-to-end training with marginal log loss can eliminate the need for detailed manual alignments. We draw the connections between the marginal log loss and a popular end-to-end training approach called connectionist temporal classification. We present a unifying framework for various end-to-end graph search-based models, such as hidden Markov models, connectionist temporal classification, and segmental models. Finally, we discuss possible extensions of segmental models to large-vocabulary sequence prediction tasks.

##### Abstract (translated by Google)
跨越输入的连续部分的段（诸如语音中的音素，命名为句子中的实体，视频中的操作）频繁地出现在序列预测问题中。分段模型（一种明确假设分段的模型）已经允许探索丰富的分段特征来进行序列预测。然而，分段模型的解码速度很慢，妨碍了使用计算上昂贵的特性。在本论文中，我们引入了判别式分段级联，这是一种多通道推理框架，它允许我们通过在保持效率的同时添加高阶特征和神经分段特征来提高精度。我们还表明，不是包含更多的特征来获得更好的精度，分段级联可以用来加速训练和解码。与常规语音识别器类似，分段模型通常以多个阶段进行训练。在第一阶段，帧分类器是手动对齐训练，然后在第二阶段，分段模型训练与手动对齐和帧分类器的输出。但是，获取手动对齐是耗时且昂贵的。我们将探索具有各种损失函数的分段模型的端到端培训，并展示边际对数损失的端到端培训如何消除对详细的手动对齐的需求。我们将边际对数损失与一种流行的端对端训练方法（称为连接主义时间分类）联系起来。我们提出了一个统一的框架，以各种端到端的图搜索为基础的模型，如隐马尔可夫模型，连接主义时间分类和分段模型。最后，我们讨论了可能将分段模型扩展到大词汇量序列预测任务。

##### URL
[https://arxiv.org/abs/1709.01572](https://arxiv.org/abs/1709.01572)

##### PDF
[https://arxiv.org/pdf/1709.01572](https://arxiv.org/pdf/1709.01572)

