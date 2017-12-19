---
layout: post
title: "Deep Visual Attention Prediction"
date: 2017-12-18 03:41:34
categories: arXiv_CV
tags: arXiv_CV Salient Attention CNN Inference Deep_Learning Prediction
author: Wenguan Wang, Jianbing Shen
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we aim to predict human eye fixation with view-free scenes based on an end-to-end deep learning architecture. Although Convolutional Neural Networks (CNNs) have made substantial improvement on human attention prediction, it is still needed to improve CNN based attention models by efficiently leveraging multi-scale features. Our visual attention network is proposed to capture hierarchical saliency information from deep, coarse layers with global saliency information to shallow, fine layers with local saliency response. Our model is based on a skip-layer network structure, which predicts human attention from multiple convolutional layers with various reception fields. Final saliency prediction is achieved via the cooperation of those global and local predictions. Our model is learned in a deep supervision manner, where supervision is directly fed into multi-level layers, instead of previous approaches of providing supervision only at the output layer and propagating this supervision back to earlier layers. Our model thus incorporates multi-level saliency predictions within a single network, which significantly decreases the redundancy of previous approaches of learning multiple network streams with different input scales. Extensive experimental analysis on various challenging benchmark datasets demonstrate our method yields state-of-the-art performance with competitive inference time.

##### Abstract (translated by Google)
在这项工作中，我们的目标是预测基于端到端深度学习架构的无视点场景的人眼固定。尽管卷积神经网络（CNNs）在人类关注预测方面取得了实质性的进展，但仍然需要通过有效利用多尺度特征来改善基于CNN的注意模型。我们的视觉关注网络被提出来从具有全局显着性信息的深层，粗层到具有局部显着性响应的浅层，精细层捕获分层显着性信息。我们的模型基于跳层网络结构，它预测了来自具有各种接收场的多个卷积层的人的注意力。最终的显着性预测是通过全球和本地预测的合作来实现的。我们的模型是以深层次的监督方式学习的，监督直接反馈到多层次的层面，而不是以前只在输出层提供监督的方法，并把监督传播到更早的层次。因此，我们的模型将单一网络中的多级显着性预测结合起来，这显着降低了以前用不同输入尺度学习多个网络流的方法的冗余度。对各种具有挑战性的基准数据集进行广泛的实验分析，证明了我们的方法在竞争推理时间内获得了最先进的性能。

##### URL
[http://arxiv.org/abs/1705.02544](http://arxiv.org/abs/1705.02544)

##### PDF
[http://arxiv.org/pdf/1705.02544](http://arxiv.org/pdf/1705.02544)

