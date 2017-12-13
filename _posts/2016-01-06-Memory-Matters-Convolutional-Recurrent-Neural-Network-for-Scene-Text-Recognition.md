---
layout: post
title: "Memory Matters: Convolutional Recurrent Neural Network for Scene Text Recognition"
date: 2016-01-06 07:36:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Recognition
author: Guo Qiang, Tu Dan, Li Guohui, Lei Jun
mathjax: true
---

* content
{:toc}

##### Abstract
Text recognition in natural scene is a challenging problem due to the many factors affecting text appearance. In this paper, we presents a method that directly transcribes scene text images to text without needing of sophisticated character segmentation. We leverage recent advances of deep neural networks to model the appearance of scene text images with temporal dynamics. Specifically, we integrates convolutional neural network (CNN) and recurrent neural network (RNN) which is motivated by observing the complementary modeling capabilities of the two models. The main contribution of this work is investigating how temporal memory helps in an segmentation free fashion for this specific problem. By using long short-term memory (LSTM) blocks as hidden units, our model can retain long-term memory compared with HMMs which only maintain short-term state dependences. We conduct experiments on Street View House Number dataset containing highly variable number images. The results demonstrate the superiority of the proposed method over traditional HMM based methods.

##### Abstract (translated by Google)
自然场景中的文本识别是一个具有挑战性的问题，因为影响文本外观的因素很多。在本文中，我们提出了一种方法，直接转录场景文本图像文本，而不需要复杂的字符分割。我们利用深度神经网络的最新进展来模拟具有时间动态的场景文本图像的外观。具体来说，我们集成了卷积神经网络（CNN）和递归神经网络（RNN），这是通过观察两个模型的互补建模能力来激发的。这项工作的主要贡献是调查时间记忆是如何帮助这个特定问题的分割自由的方式。通过使用长时间短记忆（LSTM）块作为隐藏单元，与仅维持短期状态依赖性的HMM相比，我们的模型可以保留长期记忆。我们在包含高度可变数字图像的街景房屋号码数据集上进行实验。结果证明了该方法优于传统的基于HMM的方法。

##### URL
[https://arxiv.org/abs/1601.01100](https://arxiv.org/abs/1601.01100)

##### PDF
[https://arxiv.org/pdf/1601.01100](https://arxiv.org/pdf/1601.01100)

