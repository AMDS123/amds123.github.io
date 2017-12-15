---
layout: post
title: "Analyzing Hidden Representations in End-to-End Automatic Speech Recognition Systems"
date: 2017-09-13 18:02:53
categories: arXiv_CL
tags: arXiv_CL GAN Speech_Recognition CNN Classification Recognition
author: Yonatan Belinkov, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
Neural models have become ubiquitous in automatic speech recognition systems. While neural networks are typically used as acoustic models in more complex systems, recent studies have explored end-to-end speech recognition systems based on neural networks, which can be trained to directly predict text from input acoustic features. Although such systems are conceptually elegant and simpler than traditional systems, it is less obvious how to interpret the trained models. In this work, we analyze the speech representations learned by a deep end-to-end model that is based on convolutional and recurrent layers, and trained with a connectionist temporal classification (CTC) loss. We use a pre-trained model to generate frame-level features which are given to a classifier that is trained on frame classification into phones. We evaluate representations from different layers of the deep model and compare their quality for predicting phone labels. Our experiments shed light on important aspects of the end-to-end model such as layer depth, model complexity, and other design choices.

##### Abstract (translated by Google)
神经模型已经在自动语音识别系统中无处不在。虽然神经网络通常被用作更复杂系统的声学模型，但最近的研究已经探索了基于神经网络的端到端语音识别系统，该系统可以被训练直接从输入声学特征预测文本。尽管这样的系统在概念上比传统系统更为优雅和简单，但是如何解释训练过的模型并不那么明显。在这项工作中，我们分析了基于卷积层和复发层的深层端到端模型学习的语音表示，并用联结主义时态分类（CTC）丢失进行训练。我们使用预先训练的模型来生成帧级别的特征，这些特征被分配给经过帧分类手机训练的分类器。我们评估来自深层模型不同层次的表示，并比较它们的质量来预测手机标签。我们的实验揭示了端到端模型的重要方面，如层深度，模型复杂性和其他设计选择。

##### URL
[https://arxiv.org/abs/1709.04482](https://arxiv.org/abs/1709.04482)

##### PDF
[https://arxiv.org/pdf/1709.04482](https://arxiv.org/pdf/1709.04482)

