---
layout: post
title: "A Novel Embedding Model for Knowledge Base Completion Based on Convolutional Neural Network"
date: 2017-12-06 10:41:47
categories: arXiv_CL
tags: arXiv_CL CNN
author: Dai Quoc Nguyen, Tu Dinh Nguyen, Dat Quoc Nguyen, Dinh Phung
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel embedding method for knowledge base completion task. Our approach advances state-of-the-art (SOTA) by employing a convolutional neural network (CNN) for the task which can capture global relationships and transitional characteristics. We represent each triple (head entity, relation, tail entity) as a 3-column matrix which is the input for the convolution layer. Different filters having a same shape of 1x3 are operated over the input matrix to produce different feature maps which are then concatenated into a single feature vector. This vector is used to return a score for the triple via a dot product. The returned score is used to predict whether the triple is valid or not. Experiments show that ConvKB achieves better link prediction results than previous SOTA models on two current benchmark datasets WN18RR and FB15k-237.

##### Abstract (translated by Google)
我们介绍一种新的知识库完成任务的嵌入方法。我们的方法通过使用卷积神经网络（CNN）来实现最先进的技术（SOTA），以完成可以捕捉全局关系和过渡特征的任务。我们将每个三元组（头实体，关系，尾实体）表示为一个3列矩阵，它是卷积层的输入。具有相同形状的1×3的不同滤波器在输入矩阵上操作以产生不同的特征图，然后将其连接成单个特征向量。该向量用于通过点积返回三元组的分数。返回的分数用于预测三元组是否有效。实验表明，ConvKB在两个当前的基准数据集WN18RR和FB15k-237上获得了比以前的SOTA模型更好的链接预测结果。

##### URL
[http://arxiv.org/abs/1712.02121](http://arxiv.org/abs/1712.02121)

##### PDF
[http://arxiv.org/pdf/1712.02121](http://arxiv.org/pdf/1712.02121)

