---
layout: post
title: "FaceNet2ExpNet: Regularizing a Deep Face Recognition Net for Expression Recognition"
date: 2016-09-22 00:59:45
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Hui Ding, Shaohua Kevin Zhou, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Relatively small data sets available for expression recognition research make the training of deep networks for expression recognition very challenging. Although fine-tuning can partially alleviate the issue, the performance is still below acceptable levels as the deep features probably contain redun- dant information from the pre-trained domain. In this paper, we present FaceNet2ExpNet, a novel idea to train an expression recognition network based on static images. We first propose a new distribution function to model the high-level neurons of the expression network. Based on this, a two-stage training algorithm is carefully designed. In the pre-training stage, we train the convolutional layers of the expression net, regularized by the face net; In the refining stage, we append fully- connected layers to the pre-trained convolutional layers and train the whole network jointly. Visualization shows that the model trained with our method captures improved high-level expression semantics. Evaluations on four public expression databases, CK+, Oulu-CASIA, TFD, and SFEW demonstrate that our method achieves better results than state-of-the-art.

##### Abstract (translated by Google)
可用于表达识别研究的相对较小的数据集使得用于表达识别的深度网络的训练非常具有挑战性。虽然微调可以部分缓解这个问题，但是性能仍然低于可接受的水平，因为深度特征可能包含来自预先训练的域的冗余信息。在本文中，我们提出了FaceNet2ExpNet，一种基于静态图像的表达识别网络的新思路。我们首先提出一种新的分布函数来模拟表达网络的高级神经元。基于此，仔细设计了一个两阶段训练算法。在训练前阶段，我们训练表情网络的卷积层，由人脸网络规则化;在精化阶段，我们将完全连接的层添加到预训练的卷积层，并联合训练整个网络。可视化表明，用我们的方法训练的模型捕捉到改进的高级表达语义。对四个公共表达数据库CK +，Oulu-CASIA，TFD和SFEW的评估表明，我们的方法比现有技术获得更好的结果。

##### URL
[https://arxiv.org/abs/1609.06591](https://arxiv.org/abs/1609.06591)

##### PDF
[https://arxiv.org/pdf/1609.06591](https://arxiv.org/pdf/1609.06591)

