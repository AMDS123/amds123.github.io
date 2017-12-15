---
layout: post
title: "Drawing and Recognizing Chinese Characters with Recurrent Neural Network"
date: 2016-06-21 12:35:31
categories: arXiv_CV
tags: arXiv_CV Knowledge Embedding CNN RNN Deep_Learning Recognition
author: Xu-Yao Zhang, Fei Yin, Yan-Ming Zhang, Cheng-Lin Liu, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep learning based approaches have achieved great success on handwriting recognition. Chinese characters are among the most widely adopted writing systems in the world. Previous research has mainly focused on recognizing handwritten Chinese characters. However, recognition is only one aspect for understanding a language, another challenging and interesting task is to teach a machine to automatically write (pictographic) Chinese characters. In this paper, we propose a framework by using the recurrent neural network (RNN) as both a discriminative model for recognizing Chinese characters and a generative model for drawing (generating) Chinese characters. To recognize Chinese characters, previous methods usually adopt the convolutional neural network (CNN) models which require transforming the online handwriting trajectory into image-like representations. Instead, our RNN based approach is an end-to-end system which directly deals with the sequential structure and does not require any domain-specific knowledge. With the RNN system (combining an LSTM and GRU), state-of-the-art performance can be achieved on the ICDAR-2013 competition database. Furthermore, under the RNN framework, a conditional generative model with character embedding is proposed for automatically drawing recognizable Chinese characters. The generated characters (in vector format) are human-readable and also can be recognized by the discriminative RNN model with high accuracy. Experimental results verify the effectiveness of using RNNs as both generative and discriminative models for the tasks of drawing and recognizing Chinese characters.

##### Abstract (translated by Google)
最近的基于深度学习的方法在手写识别上取得了很大的成功。汉字是世界上应用最广泛的书写系统之一。以前的研究主要集中在识别手写汉字。然而，认识只是理解语言的一个方面，另一个具有挑战性和有趣的任务是教一台机器自动书写（象形）汉字。在本文中，我们提出了一种使用递归神经网络（RNN）作为识别汉字的判别模型和生成汉字的生成模型的框架。为了识别汉字，以前的方法通常采用卷积神经网络（CNN）模型，其需要将在线手写轨迹转换为图像表示。相反，我们的基于RNN的方法是直接处理顺序结构并且不需要任何领域特定知识的端到端系统。通过RNN系统（结合LSTM和GRU），可以在ICDAR-2013比赛数据库中实现最先进的性能。此外，在RNN框架下，提出了一种带有字符嵌入的条件生成模型，用于自动绘制可识别的汉字。生成的字符（矢量格式）是人类可读的，并且可以通过区分性RNN模型高准确度地识别。实验结果验证了使用RNN作为绘图和识别汉字任务的生成模式和判别模式的有效性。

##### URL
[https://arxiv.org/abs/1606.06539](https://arxiv.org/abs/1606.06539)

##### PDF
[https://arxiv.org/pdf/1606.06539](https://arxiv.org/pdf/1606.06539)

