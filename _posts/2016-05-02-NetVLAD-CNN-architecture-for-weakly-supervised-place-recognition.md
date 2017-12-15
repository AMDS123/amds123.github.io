---
layout: post
title: "NetVLAD: CNN architecture for weakly supervised place recognition"
date: 2016-05-02 15:42:41
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Retrieval Weakly_Supervised CNN Recognition
author: Relja Arandjelović, Petr Gronat, Akihiko Torii, Tomas Pajdla, Josef Sivic
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of large scale visual place recognition, where the task is to quickly and accurately recognize the location of a given query photograph. We present the following three principal contributions. First, we develop a convolutional neural network (CNN) architecture that is trainable in an end-to-end manner directly for the place recognition task. The main component of this architecture, NetVLAD, is a new generalized VLAD layer, inspired by the "Vector of Locally Aggregated Descriptors" image representation commonly used in image retrieval. The layer is readily pluggable into any CNN architecture and amenable to training via backpropagation. Second, we develop a training procedure, based on a new weakly supervised ranking loss, to learn parameters of the architecture in an end-to-end manner from images depicting the same places over time downloaded from Google Street View Time Machine. Finally, we show that the proposed architecture significantly outperforms non-learnt image representations and off-the-shelf CNN descriptors on two challenging place recognition benchmarks, and improves over current state-of-the-art compact image representations on standard image retrieval benchmarks.

##### Abstract (translated by Google)
我们解决大规模视觉地点识别的问题，其任务是快速准确地识别给定查询照片的位置。我们提出以下三个主要贡献。首先，我们开发了一种卷积神经网络（CNN）架构，可以直接针对地点识别任务进行端对端训练。该体系结构的主要组成部分NetVLAD是一个新的广义VLAD层，受图像检索中常用的“局部聚合描述符向量”图像表示的启发。该层很容易插入到任何CNN体系结构中，并且可以通过反向传播进行训练。其次，我们开发了一个基于新的弱监督排名损失的训练程序，从Google Street View Time Machine下载的随时间变化的图像以端对端的方式学习体系结构的参数。最后，我们展示了所提出的体系结构在两个具有挑战性的场所识别基准上明显优于非学习的图像表示和现成CNN描述符，并且改进了标准图像检索基准上当前最先进的紧凑图像表示。

##### URL
[https://arxiv.org/abs/1511.07247](https://arxiv.org/abs/1511.07247)

##### PDF
[https://arxiv.org/pdf/1511.07247](https://arxiv.org/pdf/1511.07247)

