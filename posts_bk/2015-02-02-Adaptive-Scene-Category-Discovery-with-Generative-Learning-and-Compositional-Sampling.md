---
layout: post
title: "Adaptive Scene Category Discovery with Generative Learning and Compositional Sampling"
date: 2015-02-02 06:33:51
categories: arXiv_CV
tags: arXiv_CV Inference
author: Liang Lin, Ruimao Zhang, Xiaohua Duan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates a general framework to discover categories of unlabeled scene images according to their appearances (i.e., textures and structures). We jointly solve the two coupled tasks in an unsupervised manner: (i) classifying images without pre-determining the number of categories, and (ii) pursuing generative model for each category. In our method, each image is represented by two types of image descriptors that are effective to capture image appearances from different aspects. By treating each image as a graph vertex, we build up an graph, and pose the image categorization as a graph partition process. Specifically, a partitioned sub-graph can be regarded as a category of scenes, and we define the probabilistic model of graph partition by accumulating the generative models of all separated categories. For efficient inference with the graph, we employ a stochastic cluster sampling algorithm, which is designed based on the Metropolis-Hasting mechanism. During the iterations of inference, the model of each category is analytically updated by a generative learning algorithm. In the experiments, our approach is validated on several challenging databases, and it outperforms other popular state-of-the-art methods. The implementation details and empirical analysis are presented as well.

##### Abstract (translated by Google)
本文研究了一个通用框架，根据它们的外观（即纹理和结构）发现未标记场景图像的类别。我们以无监督的方式共同解决两个耦合的任务：（i）在不预先确定类别数量的情况下对图像进行分类，（ii）为每个类别寻求生成模型。在我们的方法中，每个图像由两种类型的图像描述符表示，这些图像描述符有效地从不同方面捕捉图像外观。通过将每个图像视为一个图顶点，我们建立一个图，并将图像分类作为一个图分割过程。具体而言，分割子图可以看作是一类场景，通过对所有分类类的生成模型进行累加，定义了图划分的概率模型。为了有效地推理图，我们采用了基于Metropolis-Hasting机制的随机整群抽样算法。在推理迭代过程中，每个类别的模型通过生成学习算法进行分析更新。在实验中，我们的方法在几个具有挑战性的数据库上得到验证，并且胜过了其他流行的最先进的方法。介绍了实施细节和实证分析。

##### URL
[https://arxiv.org/abs/1502.00374](https://arxiv.org/abs/1502.00374)

##### PDF
[https://arxiv.org/pdf/1502.00374](https://arxiv.org/pdf/1502.00374)

