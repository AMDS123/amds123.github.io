---
layout: post
title: "Visual Question Answering as a Meta Learning Task"
date: 2017-11-22 02:04:31
categories: arXiv_CV
tags: arXiv_CV VQA
author: Damien Teney, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
The predominant approach to Visual Question Answering (VQA) demands that the model represents within its weights all of the information required to answer any question about any image. Learning this information from any real training set seems unlikely, and representing it in a reasonable number of weights doubly so. We propose instead to approach VQA as a meta learning task, thus separating the question answering method from the information required. At test time, the method is provided with a support set of example questions/answers, over which it reasons to resolve the given question. The support set is not fixed and can be extended without retraining, thereby expanding the capabilities of the model. To exploit this dynamically provided information, we adapt a state-of-the-art VQA model with two techniques from the recent meta learning literature, namely prototypical networks and meta networks. Experiments demonstrate the capability of the system to learn to produce completely novel answers (i.e. never seen during training) from examples provided at test time. In comparison to the existing state of the art, the proposed method produces qualitatively distinct results with higher recall of rare answers, and a better sample efficiency that allows training with little initial data. More importantly, it represents an important step towards vision-and-language methods that can learn and reason on-the-fly.

##### Abstract (translated by Google)
视觉问题回答（VQA）的主要方法要求模型在其权重范围内表示回答关于任何图像的任何问题所需的所有信息。从任何真正的训练集中学习这些信息似乎是不太可能的，并且用合理数量的权重代表它。我们建议将VQA作为元学习任务，从而将问答方法与所需信息分开。在测试的时候，该方法提供了一套支持的示例问题/答案，通过这个问题/答案可以解决给定的问题。支持集不是固定的，可以在不进行再训练的情况下进行扩展，从而扩展了模型的功能。为了利用这种动态提供的信息，我们使用最近元学习文献中的两种技术（即原型网络和元网络）来调整最先进的VQA模型。实验证明了系统能够学习从测试时提供的例子中产生完全新颖的答案（即在训练期间从未见过）。与现有技术相比，所提出的方法产生定性明显的结果，具有更高的罕见答案回忆，以及更好的样本效率，允许使用少量初始数据进行训练。更重要的是，它代表了一个向视觉和语言方法迈进的重要一步，可以在飞行中学习和推理。

##### URL
[https://arxiv.org/abs/1711.08105](https://arxiv.org/abs/1711.08105)

##### PDF
[https://arxiv.org/pdf/1711.08105](https://arxiv.org/pdf/1711.08105)

