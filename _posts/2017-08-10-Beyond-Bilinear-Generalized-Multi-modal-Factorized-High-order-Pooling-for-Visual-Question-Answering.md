---
layout: post
title: "Beyond Bilinear: Generalized Multi-modal Factorized High-order Pooling for Visual Question Answering"
date: 2017-08-10 09:09:23
categories: arXiv_CV
tags: arXiv_CV QA Attention Prediction Relation VQA
author: Zhou Yu, Jun Yu, Chenchao Xiang, Jianping Fan, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Visual question answering (VQA) is challenging because it requires a simultaneous understanding of both visual content of images and textual content of questions. To support the VQA task, we need to find good solutions for the following three issues: 1) fine-grained feature representations for both the image and the question; 2) multi-modal feature fusion that is able to capture the complex interactions between multi-modal features; 3) automatic answer prediction that is able to consider the complex correlations between multiple diverse answers for the same question. For fine-grained image and question representations, a `co-attention' mechanism is developed by using a deep neural network architecture to jointly learn the attentions for both the image and the question, which can allow us to reduce the irrelevant features effectively and obtain more discriminative features for image and question representations. For multi-modal feature fusion, a generalized Multi-modal Factorized High-order pooling approach (MFH) is developed to achieve more effective fusion of multi-modal features by exploiting their correlations sufficiently, which can further result in superior VQA performance as compared with the state-of-the-art approaches. For answer prediction, the KL (Kullback-Leibler) divergence is used as the loss function to achieve more accurate characterization of the complex correlations between multiple diverse answers with same or similar meaning, which can allow us to achieve faster convergence rate and obtain slightly better accuracy on answer prediction. A deep neural network architecture is designed to integrate all these aforementioned modules into one unified model for achieving superior VQA performance. With an ensemble of 9 models, we achieve the state-of-the-art performance on the large-scale VQA datasets and win the runner-up in the VQA Challenge 2017.

##### Abstract (translated by Google)
视觉问答（VQA）具有挑战性，因为它需要同时理解图像的视觉内容和问题的文本内容。为了支持VQA任务，我们需要为以下三个问题找到好的解决方案：1）图像和问题的细粒度特征表示; 2）多模态特征融合，能够捕捉多模态特征之间复杂的相互作用; 3）自动答案预测能够考虑同一问题的多种不同答案之间的复杂相关性。对于细粒度的图像和问题表示，通过使用深度神经网络体系结构共同学习图像和问题的注意力，可以使我们有效地减少不相关的特征，获得“共同关注”机制更多的图像和问题表征的判别特征。对于多模态特征融合，开发了一种广义多模式分解高阶汇聚方法（MFH），通过充分利用它们之间的相关性，实现更有效的多模态特征融合，从而进一步提高VQA性能最先进的方法。对于答案预测，使用KL（Kullback-Leibler）散度作为损失函数，以更精确地表征具有相同或相似含义的多个不同答案之间的复杂相关性，这可以使我们获得更快的收敛速度并获得稍好答案预测的准确性。深度神经网络架构被设计为将所有上述模块集成到一个统一模型中，以实现优越的VQA性能。通过9个模型的合奏，我们在大规模VQA数据集上实现了最先进的性能，并赢得了2015年VQA挑战赛的亚军。

##### URL
[https://arxiv.org/abs/1708.03619](https://arxiv.org/abs/1708.03619)

##### PDF
[https://arxiv.org/pdf/1708.03619](https://arxiv.org/pdf/1708.03619)

