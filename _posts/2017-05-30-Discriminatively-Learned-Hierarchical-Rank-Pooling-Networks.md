---
layout: post
title: "Discriminatively Learned Hierarchical Rank Pooling Networks"
date: 2017-05-30 00:43:16
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification Recognition
author: Basura Fernando, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present novel temporal encoding methods for action and activity classification by extending the unsupervised rank pooling temporal encoding method in two ways. First, we present "discriminative rank pooling" in which the shared weights of our video representation and the parameters of the action classifiers are estimated jointly for a given training dataset of labelled vector sequences using a bilevel optimization formulation of the learning problem. When the frame level features vectors are obtained from a convolutional neural network (CNN), we rank pool the network activations and jointly estimate all parameters of the model, including CNN filters and fully-connected weights, in an end-to-end manner which we coined as "end-to-end trainable rank pooled CNN". Importantly, this model can make use of any existing convolutional neural network architecture (e.g., AlexNet or VGG) without modification or introduction of additional parameters. Then, we extend rank pooling to a high capacity video representation, called "hierarchical rank pooling". Hierarchical rank pooling consists of a network of rank pooling functions, which encode temporal semantics over arbitrary long video clips based on rich frame level features. By stacking non-linear feature functions and temporal sub-sequence encoders one on top of the other, we build a high capacity encoding network of the dynamic behaviour of the video. The resulting video representation is a fixed-length feature vector describing the entire video clip that can be used as input to standard machine learning classifiers. We demonstrate our approach on the task of action and activity recognition. Obtained results are comparable to state-of-the-art methods on three important activity recognition benchmarks with classification performance of 76.7% mAP on Hollywood2, 69.4% on HMDB51, and 93.6% on UCF101.

##### Abstract (translated by Google)
在这项工作中，我们提出了新的时间编码方法的行动和活动分类，通过扩展无监督的秩池时间编码方法在两个方面。首先，我们提出了“歧视性排名池”，其中我们的视频表示的共享权重和行动分类器的参数联合估计使用学习问题的双层优化公式的标记向量序列的给定训练数据集。当从卷积神经网络（CNN）获得帧级特征向量时，我们对网络激活进行排序，并以端到端的方式联合估计模型的所有参数，包括CNN滤波器和全连接权重，其中我们创造了“端到端的可训练等级汇集CNN”。重要的是，该模型可以使用任何现有的卷积神经网络架构（例如，AlexNet或VGG）而无需修改或引入额外的参数。然后，我们将排名池扩展到一个高容量的视频表示，称为“层次级联池”。分层排序池由排序池功能网络组成，其基于丰富的帧级别特征对任意长视频片段上的时间语义进行编码。通过将非线性特征函数和时间子序列编码器叠加在一起，构建了视频动态行为的高容量编码网络。得到的视频表示是一个固定长度的特征向量，描述整个视频剪辑，可以用作标准机器学习分类器的输入。我们在行动和活动承认的任务上展示我们的方法。在三项重要的活动识别基准中，获得的结果与最先进的方法相当，其中好莱坞的mAP分类性能为76.7％，HMDB51为69.4％，UCF101为93.6％。

##### URL
[https://arxiv.org/abs/1705.10420](https://arxiv.org/abs/1705.10420)

##### PDF
[https://arxiv.org/pdf/1705.10420](https://arxiv.org/pdf/1705.10420)

