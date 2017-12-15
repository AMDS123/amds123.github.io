---
layout: post
title: "Unsupervised Learning of Visual Structure using Predictive Generative Networks"
date: 2016-01-20 05:50:46
categories: arXiv_CV
tags: arXiv_CV Adversarial Face RNN Classification Prediction
author: William Lotter, Gabriel Kreiman, David Cox
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to predict future states of the environment is a central pillar of intelligence. At its core, effective prediction requires an internal model of the world and an understanding of the rules by which the world changes. Here, we explore the internal models developed by deep neural networks trained using a loss based on predicting future frames in synthetic video sequences, using a CNN-LSTM-deCNN framework. We first show that this architecture can achieve excellent performance in visual sequence prediction tasks, including state-of-the-art performance in a standard 'bouncing balls' dataset (Sutskever et al., 2009). Using a weighted mean-squared error and adversarial loss (Goodfellow et al., 2014), the same architecture successfully extrapolates out-of-the-plane rotations of computer-generated faces. Furthermore, despite being trained end-to-end to predict only pixel-level information, our Predictive Generative Networks learn a representation of the latent structure of the underlying three-dimensional objects themselves. Importantly, we find that this representation is naturally tolerant to object transformations, and generalizes well to new tasks, such as classification of static images. Similar models trained solely with a reconstruction loss fail to generalize as effectively. We argue that prediction can serve as a powerful unsupervised loss for learning rich internal representations of high-level object features.

##### Abstract (translated by Google)
预测未来环境状况的能力是情报的核心支柱。其核心在于有效的预测需要一个世界的内部模型和对世界变化的规则的理解。在这里，我们使用CNN-LSTM-deCNN框架，探索由基于预测合成视频序列中未来帧的损失训练的深度神经网络开发的内部模型。我们首先表明，这种架构可以在视觉序列预测任务中取得优异的性能，包括标准的“弹跳球”数据集中的最新性能（Sutskever et al。，2009）。使用加权均方误差和对抗性损失（Goodfellow等，2014），相同的体系结构成功地推断了计算机生成的面的平面外旋转（out-of-the-plane rotation）。此外，尽管经过端对端训练仅预测像素级信息，但我们的Predictive Generative Networks可以学习潜在的三维物体本身的潜在结构。重要的是，我们发现这种表示对于对象转换自然是容忍的，并且很好地适用于新的任务，例如静态图像的分类。仅仅用重建损失训练的类似模型不能一概而论。我们认为，预测可以作为一个强大的无监督损失学习丰富的高层次的对象特征的内部表示。

##### URL
[https://arxiv.org/abs/1511.06380](https://arxiv.org/abs/1511.06380)

##### PDF
[https://arxiv.org/pdf/1511.06380](https://arxiv.org/pdf/1511.06380)

