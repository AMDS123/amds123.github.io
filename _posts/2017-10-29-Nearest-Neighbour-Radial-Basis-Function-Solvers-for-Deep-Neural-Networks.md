---
layout: post
title: "Nearest Neighbour Radial Basis Function Solvers for Deep Neural Networks"
date: 2017-10-29 06:26:27
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Classification
author: Benjamin J. Meyer, Ben Harwood, Tom Drummond
mathjax: true
---

* content
{:toc}

##### Abstract
We present a radial basis function solver for convolutional neural networks that can be directly applied to both distance metric learning and classification problems. Our method treats all training features from a deep neural network as radial basis function centres and computes loss by summing the influence of a feature's nearby centres in the embedding space. Having a radial basis function centred on each training feature is made scalable by treating it as an approximate nearest neighbour search problem. End-to-end learning of the network and solver is carried out, mapping high dimensional features into clusters of the same class. This results in a well formed embedding space, where semantically related instances are likely to be located near one another, regardless of whether or not the network was trained on those classes. The same loss function is used for both the metric learning and classification problems. We show that our radial basis function solver outperforms state-of-the-art embedding approaches on the Stanford Cars196 and CUB-200-2011 datasets. Additionally, we show that when used as a classifier, our method outperforms a conventional softmax classifier on the CUB-200-2011, Stanford Cars196, Oxford 102 Flowers and Leafsnap fine-grained classification datasets.

##### Abstract (translated by Google)
我们提出了一个卷积神经网络的径向基函数求解器，可以直接应用于距离度量学习和分类问题。我们的方法将来自深度神经网络的所有训练特征视为径向基函数中心，并通过将特征的附近中心在嵌入空间中的影响相加来计算损失。以每个训练特征为中心的径向基函数通过将其视为近似最近邻搜索问题而被放大。对网络和求解器进行端到端的学习，将高维特征映射到同一类的簇中。这导致形成一个良好的嵌入空间，语义相关的实例可能位于彼此靠近的位置，而不管网络是否在这些类上训练。度量学习和分类问题都使用相同的损失函数。我们展示了我们的径向基函数求解器胜过了斯坦福大学的汽车196和CUB-200-2011数据集上的最先进的嵌入方法。此外，我们显示，当用作分类器时，我们的方法胜过传统的softmax分类器在CUB-200-2011，Stanford Cars196，Oxford 102 Flowers and Leafsnap细粒度分类数据集上。

##### URL
[https://arxiv.org/abs/1705.09780](https://arxiv.org/abs/1705.09780)

##### PDF
[https://arxiv.org/pdf/1705.09780](https://arxiv.org/pdf/1705.09780)

