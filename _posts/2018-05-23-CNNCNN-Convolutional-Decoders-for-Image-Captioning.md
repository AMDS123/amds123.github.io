---
layout: post
title: "CNN+CNN: Convolutional Decoders for Image Captioning"
date: 2018-05-23 09:16:59
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption CNN RNN
author: Qingzhong Wang, Antoni B. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning is a challenging task that combines the field of computer vision and natural language processing. A variety of approaches have been proposed to achieve the goal of automatically describing an image, and recurrent neural network (RNN) or long-short term memory (LSTM) based models dominate this field. However, RNNs or LSTMs cannot be calculated in parallel and ignore the underlying hierarchical structure of a sentence. In this paper, we propose a framework that only employs convolutional neural networks (CNNs) to generate captions. Owing to parallel computing, our basic model is around 3 times faster than NIC (an LSTM-based model) during training time, while also providing better results. We conduct extensive experiments on MSCOCO and investigate the influence of the model width and depth. Compared with LSTM-based models that apply similar attention mechanisms, our proposed models achieves comparable scores of BLEU-1,2,3,4 and METEOR, and higher scores of CIDEr. We also test our model on the paragraph annotation dataset, and get higher CIDEr score compared with hierarchical LSTMs

##### Abstract (translated by Google)
图像字幕是结合了计算机视觉和自然语言处理领域的一项具有挑战性的任务。已经提出了各种方法来实现自动描述图像的目标，并且基于递归神经网络（RNN）或长期短期记忆（LSTM）的模型在这个领域占主导地位。但是，RNN或LSTM不能并行计算，而忽略句子的底层分层结构。在本文中，我们提出了一个仅使用卷积神经网络（CNN）生成字幕的框架。由于并行计算，我们的基本模型在培训期间比NIC（基于LSTM的模型）快3倍，同时也提供了更好的结果。我们对MSCOCO进行了广泛的实验，并研究了模型宽度和深度的影响。与应用类似注意机制的基于LSTM的模型相比，我们提出的模型可以达到BLEU-1,2,3,4和METEOR的可比分数，以及CIDEr的更高分数。我们还在段落注释数据集上测试了我们的模型，并与分层LSTM相比获得了更高的CIDEr评分

##### URL
[http://arxiv.org/abs/1805.09019](http://arxiv.org/abs/1805.09019)

##### PDF
[http://arxiv.org/pdf/1805.09019](http://arxiv.org/pdf/1805.09019)

