---
layout: post
title: "Input Fast-Forwarding for Better Deep Learning"
date: 2017-05-23 18:57:08
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Ahmed Ibrahim, A. Lynn Abbott, Mohamed E. Hussein
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a new architectural framework, known as input fast-forwarding, that can enhance the performance of deep networks. The main idea is to incorporate a parallel path that sends representations of input values forward to deeper network layers. This scheme is substantially different from "deep supervision" in which the loss layer is re-introduced to earlier layers. The parallel path provided by fast-forwarding enhances the training process in two ways. First, it enables the individual layers to combine higher-level information (from the standard processing path) with lower-level information (from the fast-forward path). Second, this new architecture reduces the problem of vanishing gradients substantially because the fast-forwarding path provides a shorter route for gradient backpropagation. In order to evaluate the utility of the proposed technique, a Fast-Forward Network (FFNet), with 20 convolutional layers along with parallel fast-forward paths, has been created and tested. The paper presents empirical results that demonstrate improved learning capacity of FFNet due to fast-forwarding, as compared to GoogLeNet (with deep supervision) and CaffeNet, which are 4x and 18x larger in size, respectively. All of the source code and deep learning models described in this paper will be made available to the entire research community

##### Abstract (translated by Google)
本文介绍了一种新的架构框架，称为输入快速转发，可以提高深度网络的性能。主要思想是将并行路径发送到更深的网络层。这种方案与将“损失层”重新引入到更早层的“深度监督”有很大不同。快进提供的并行路径以两种方式增强了训练过程。首先，它使各层能够将更高级别的信息（来自标准处理路径）与更低级别的信息（来自快进路径）相结合。其次，这种新的体系结构大大减少了渐变消失的问题，因为快进路径为渐变反向传播提供了较短的路径。为了评估所提出的技术的效用，已经创建并测试了具有20个卷积层以及并行快进路径的快速前向网络（FFNet）。本文提出的实证结果表明，与GoogLeNet（深度监督）和CaffeNet相比，由于快速转发，FFNet提高了学习能力，分别是4倍和18倍的规模。本文所描述的所有源代码和深度学习模型都将提供给整个研究团体

##### URL
[https://arxiv.org/abs/1705.08479](https://arxiv.org/abs/1705.08479)

##### PDF
[https://arxiv.org/pdf/1705.08479](https://arxiv.org/pdf/1705.08479)

