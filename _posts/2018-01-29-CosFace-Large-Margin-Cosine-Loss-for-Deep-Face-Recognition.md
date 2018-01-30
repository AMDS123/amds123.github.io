---
layout: post
title: "CosFace: Large Margin Cosine Loss for Deep Face Recognition"
date: 2018-01-29 09:23:55
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Hao Wang, Yitong Wang, Zheng Zhou, Xing Ji, Zhifeng Li, Dihong Gong, Jingchao Zhou, Wei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Face recognition has achieved revolutionary advancement owing to the advancement of the deep convolutional neural network (CNN). The central task of face recognition, including face verification and identification, involves face feature discrimination. However, traditional softmax loss of deep CNN usually lacks the power of discrimination. To address this problem, recently several loss functions such as central loss \cite{centerloss}, large margin softmax loss \cite{lsoftmax}, and angular softmax loss \cite{sphereface} have been proposed. All these improvement algorithms share the same idea: maximizing inter-class variance and minimizing intra-class variance. In this paper, we design a novel loss function, namely large margin cosine loss (LMCL), to realize this idea from a different perspective. More specifically, we reformulate the softmax loss as cosine loss by L2 normalizing both features and weight vectors to remove radial variation, based on which a cosine margin term \emph{$m$} is introduced to further maximize decision margin in angular space. As a result, minimum intra-class variance and maximum inter-class variance are achieved by normalization and cosine decision margin maximization. We refer to our model trained with LMCL as CosFace. To test our approach, extensive experimental evaluations are conducted on the most popular public-domain face recognition datasets such as MegaFace Challenge, Youtube Faces (YTF) and Labeled Face in the Wild (LFW). We achieve the state-of-the-art performance on these benchmark experiments, which confirms the effectiveness of our approach.

##### Abstract (translated by Google)
由于深度卷积神经网络（CNN）的发展，人脸识别技术取得了革命性的进展。人脸识别的核心任务，包括人脸识别和识别，涉及人脸特征识别。然而，CNN深度传统的softmax损失往往缺乏歧视的力量。为了解决这个问题，最近已经提出了几种损失函数，如中心损失\中心损失}，大边缘软损失损失\引用\软最大}和角度软最大损失\引用{球面}。所有这些改进算法都有相同的想法：最大化类间方差和最小化类内方差。在本文中，我们设计了一个新的损失函数，即大边余弦损失（LMCL），从不同的角度来实现这个想法。更具体地说，我们通过L2归一化两个特征和权向量来将softmax损失重新表示为余弦损失，以消除径向变化，基于这个余弦项被引入以进一步最大化角度空间中的判决余量。因此，通过归一化和余弦决策边界最大化来实现最小类内方差和最大类间方差。我们将用LMCL训练的模型称为CosFace。为了测试我们的方法，对最流行的公共领域面部识别数据集（例如MegaFace Challenge，Youtube Faces（YTF）和野外标记脸（LFW））进行了广泛的实验评估。我们在这些基准实验上达到了最先进的性能，这证实了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1801.09414](http://arxiv.org/abs/1801.09414)

##### PDF
[http://arxiv.org/pdf/1801.09414](http://arxiv.org/pdf/1801.09414)

