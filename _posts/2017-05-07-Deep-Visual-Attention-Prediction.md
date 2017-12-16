---
layout: post
title: "Deep Visual Attention Prediction"
date: 2017-05-07 01:53:17
categories: arXiv_CV
tags: arXiv_CV Salient Attention CNN Inference Deep_Learning Prediction
author: Wenguan Wang, Jianbing Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (CNNs) have made substantial improvement on human attention prediction. There still remains room for improvement over deep learning based attention models that do not explicitly deal with scale-space feature learning problem. Our method learns to predict human eye fixation with view-free scenes based on an end-to-end deep learning architecture. The attention model captures hierarchical saliency information from deep, coarse layers with global saliency information to shallow, fine layers with local saliency response. We base our model on a skip-layer network structure, which predicts human attention from multiple convolutional layers with various reception fields. Final saliency prediction is achieved via the cooperation of those global and local predictions. Our model is learned with a deep supervision manner, where supervision is directly fed into multi-level layers, instead of previous approaches of providing supervision only at the output layer and propagating this supervision back to earlier layers. Our model thus incorporates multi-level saliency predictions within a single network, which significantly decreases the redundancy of previous approaches of learning multiple network streams with different input scales. Extensive experimental analysis on various challenging benchmark datasets demonstrate our method yields state-of-the-art performance with competitive inference time.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）已经在人类关注预测方面取得了实质性的进步。基于深度学习的注意模型还没有明确地处理尺度 - 空间特征学习问题，还有待改进。我们的方法学习预测基于端到端深度学习架构的无视点场景的人眼固定。注意模型将来自具有全局显着性信息的深层，粗层的分层显着性信息捕获到具有局部显着性响应的浅层，精细层。我们将模型建立在跳层网络结构上，该网络结构预测来自具有各种接收领域的多个卷积层的人类关注。最终的显着性预测是通过全球和本地预测的合作来实现的。我们的模型是以深层次的监督方式学习的，在这种方式下，监督直接进入到多层次层次，而不是先前只在输出层提供监督的方法，并且把监督传播到更早的层次。因此，我们的模型将单一网络中的多级显着性预测结合起来，这显着降低了以前用不同输入尺度学习多个网络流的方法的冗余度。对各种具有挑战性的基准数据集进行广泛的实验分析，证明了我们的方法在竞争推理时间内获得了最先进的性能。

##### URL
[https://arxiv.org/abs/1705.02544](https://arxiv.org/abs/1705.02544)

##### PDF
[https://arxiv.org/pdf/1705.02544](https://arxiv.org/pdf/1705.02544)

