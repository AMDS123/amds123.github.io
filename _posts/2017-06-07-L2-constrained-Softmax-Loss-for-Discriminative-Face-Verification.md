---
layout: post
title: "L2-constrained Softmax Loss for Discriminative Face Verification"
date: 2017-06-07 18:58:18
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Deep_Learning
author: Rajeev Ranjan, Carlos D. Castillo, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, the performance of face verification systems has significantly improved using deep convolutional neural networks (DCNNs). A typical pipeline for face verification includes training a deep network for subject classification with softmax loss, using the penultimate layer output as the feature descriptor, and generating a cosine similarity score given a pair of face images. The softmax loss function does not optimize the features to have higher similarity score for positive pairs and lower similarity score for negative pairs, which leads to a performance gap. In this paper, we add an L2-constraint to the feature descriptors which restricts them to lie on a hypersphere of a fixed radius. This module can be easily implemented using existing deep learning frameworks. We show that integrating this simple step in the training pipeline significantly boosts the performance of face verification. Specifically, we achieve state-of-the-art results on the challenging IJB-A dataset, achieving True Accept Rate of 0.909 at False Accept Rate 0.0001 on the face verification protocol. Additionally, we achieve state-of-the-art performance on LFW dataset with an accuracy of 99.78%, and competing performance on YTF dataset with accuracy of 96.08%.

##### Abstract (translated by Google)
近年来，使用深度卷积神经网络（DCNN），人脸验证系统的性能得到了显着改善。一个典型的人脸识别流水线包括训练一个深度网络用于softmax损失的主题分类，使用倒数第二层输出作为特征描述符，并给出一对人脸图像的余弦相似度分数。 softmax损失函数并没有对特征进行优化，使得正对的相似度得分较高，而负对的相似度得分较低，从而导致性能差距。在本文中，我们将L2约束添加到特征描述符中，限制它们位于固定半径的超球面上。这个模块可以使用现有的深度学习框架轻松实现。我们证明，将这个简单的步骤集成到训练流程中可以大大提高面部验证的性能。具体而言，我们在具有挑战性的IJB-A数据集上实现了最新的结果，在面部验证协议上以0.0001的错误接受率实现0.909的真实接受率。此外，我们在LFW数据集上实现了最新的性能，准确率为99.78％，在YTF数据集上的竞争性能为96.08％。

##### URL
[https://arxiv.org/abs/1703.09507](https://arxiv.org/abs/1703.09507)

##### PDF
[https://arxiv.org/pdf/1703.09507](https://arxiv.org/pdf/1703.09507)

