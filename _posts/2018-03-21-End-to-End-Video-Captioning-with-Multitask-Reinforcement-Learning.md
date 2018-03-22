---
layout: post
title: "End-to-End Video Captioning with Multitask Reinforcement Learning"
date: 2018-03-21 14:51:17
categories: arXiv_CV
tags: arXiv_CV Video_Caption Knowledge Reinforcement_Learning Caption CNN RNN
author: Lijun Li, Boqing Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Although end-to-end (E2E) learning has led to promising performance on a variety of tasks, it is often impeded by hardware constraints (e.g., GPU memories) and is prone to overfitting. When it comes to video captioning, one of the most challenging benchmark tasks in computer vision and machine learning, those limitations of E2E learning are especially amplified by the fact that both the input videos and output captions are lengthy sequences. Indeed, state-of-the-art methods of video captioning process video frames by convolutional neural networks and generate captions by unrolling recurrent neural networks. If we connect them in an E2E manner, the resulting model is both memory-consuming and data-hungry, making it extremely hard to train. In this paper, we propose a multitask reinforcement learning approach to training an E2E video captioning model. The main idea is to mine and construct as many effective tasks (e.g., attributes, rewards, and the captions) as possible from the human captioned videos such that they can jointly regulate the search space of the E2E neural network, from which an E2E video captioning model can be found and generalized to the testing phase. To the best of our knowledge, this is the first video captioning model that is trained end-to-end from the raw video input to the caption output. Experimental results show that such a model outperforms existing ones to a large margin on two benchmark video captioning datasets.

##### Abstract (translated by Google)
尽管端到端（E2E）学习在各种任务中带来了有希望的性能，但它经常受到硬件限制（例如，GPU存储器）的阻碍，并且易于过度拟合。当谈到视频字幕是计算机视觉和机器学习中最具挑战性的基准测试任务之一时，由于输入视频和输出字幕都是冗长的序列，这些E2E学习的局限性尤其被放大。事实上，最新的视频字幕方法通过卷积神经网络处理视频帧，并通过展开递归神经网络来生成字幕。如果我们以E2E方式连接它们，那么最终的模型既耗费内存又耗费数据，这使得训练非常困难。在本文中，我们提出了一种多任务强化学习方法来训练E2E视频字幕模型。其主要思想是尽可能多地从人工上传的视频中挖掘和构建尽可能多的有效任务（例如属性，奖励和字幕），以便他们可以共同调节E2E神经网络的搜索空间，从中可以获得一个E2E视频字幕模型可以被发现并推广到测试阶段。据我们所知，这是第一个从原始视频输入到字幕输出端到端训练的视频字幕模型。实验结果表明，这样的模型在两个基准视频字幕数据集上优于现有模型。

##### URL
[http://arxiv.org/abs/1803.07950](http://arxiv.org/abs/1803.07950)

##### PDF
[http://arxiv.org/pdf/1803.07950](http://arxiv.org/pdf/1803.07950)

