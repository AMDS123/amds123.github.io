---
layout: post
title: "ParaNet - Using Dense Blocks for Early Inference"
date: 2018-08-24 21:01:17
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Joseph Chuang, Eric Tsai, Kevin Huang, Jay Fetter
mathjax: true
---

* content
{:toc}

##### Abstract
DenseNets have been shown to be a competitive model among recent convolutional network architectures. These networks utilize Dense Blocks, which are groups of densely connected layers where the output of a hidden layer is fed in as the input of every other layer following it. In this paper, we aim to improve certain aspects of DenseNet, especially when it comes to practicality. We introduce ParaNet, a new architecture that constructs three pipelines which allow for early inference. We additionally introduce a cascading mechanism such that different pipelines are able to share parameters, as well as logit matching between the outputs of the pipelines. We separately evaluate each of the newly introduced mechanisms of ParaNet, then evaluate our proposed architecture on CIFAR-100.

##### Abstract (translated by Google)
DenseNets已被证明是最近卷积网络架构中的竞争模型。这些网络利用密集块，密集块是密集连接层的组，其中隐藏层的输出作为其后的每个其他层的输入馈入。在本文中，我们的目标是改进DenseNet的某些方面，特别是在实用性方面。我们介绍了ParaNet，这是一种构建三条管道的新架构，可以进行早期推理。我们还引入了级联机制，使得不同的管道能够共享参数，以及管道输出之间的logit匹配。我们分别评估每个新引入的ParaNet机制，然后评估我们在CIFAR-100上提出的架构。

##### URL
[http://arxiv.org/abs/1808.08308](http://arxiv.org/abs/1808.08308)

##### PDF
[http://arxiv.org/pdf/1808.08308](http://arxiv.org/pdf/1808.08308)

