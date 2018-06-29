---
layout: post
title: "Deep CNN Denoiser and Multi-layer Neighbor Component Embedding for Face Hallucination"
date: 2018-06-28 01:00:09
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Knowledge Face Embedding CNN Optimization Inference Deep_Learning Relation
author: Junjun Jiang, Yi Yu, Jinhui Hu, Suhua Tang, Jiayi Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the current face hallucination methods, whether they are shallow learning-based or deep learning-based, all try to learn a relationship model between Low-Resolution (LR) and High-Resolution (HR) spaces with the help of a training set. They mainly focus on modeling image prior through either model-based optimization or discriminative inference learning. However, when the input LR face is tiny, the learned prior knowledge is no longer effective and their performance will drop sharply. To solve this problem, in this paper we propose a general face hallucination method that can integrate model-based optimization and discriminative inference. In particular, to exploit the model based prior, the Deep Convolutional Neural Networks (CNN) denoiser prior is plugged into the super-resolution optimization model with the aid of image-adaptive Laplacian regularization. Additionally, we further develop a high-frequency details compensation method by dividing the face image to facial components and performing face hallucination in a multi-layer neighbor embedding manner. Experiments demonstrate that the proposed method can achieve promising super-resolution results for tiny input LR faces.

##### Abstract (translated by Google)
目前大多数面对幻觉的方法，无论是浅层学习还是深度学习，都尝试通过训练集学习低分辨率（LR）和高分辨率（HR）空间之间的关系模型。他们主要关注通过基于模型的优化或区分性推理学习之前的图像建模。然而，当输入的LR面很小时，所学习的先验知识不再有效，并且其性能会急剧下降。为了解决这个问题，本文提出了一种通用的面部幻觉方法，该方法可以整合基于模型的优化和区分性推理。具体而言，为了利用基于模型的先验，借助于图像自适应拉普拉斯正则化将深度卷积神经网络（CNN）降噪器先前插入到超分辨率优化模型中。此外，我们进一步开发了一种高频细节补偿方法，将人脸图像分割为人脸部分，并以多层邻居嵌入方式进行面部幻觉。实验证明，所提出的方法可以为微小输入LR面获得有前途的超分辨率结果。

##### URL
[http://arxiv.org/abs/1806.10726](http://arxiv.org/abs/1806.10726)

##### PDF
[http://arxiv.org/pdf/1806.10726](http://arxiv.org/pdf/1806.10726)

