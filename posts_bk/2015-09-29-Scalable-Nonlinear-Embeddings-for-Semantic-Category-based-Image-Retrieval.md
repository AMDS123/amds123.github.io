---
layout: post
title: "Scalable Nonlinear Embeddings for Semantic Category-based Image Retrieval"
date: 2015-09-29 19:41:33
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding
author: Gaurav Sharma, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel algorithm for the task of supervised discriminative distance learning by nonlinearly embedding vectors into a low dimensional Euclidean space. We work in the challenging setting where supervision is with constraints on similar and dissimilar pairs while training. The proposed method is derived by an approximate kernelization of a linear Mahalanobis-like distance metric learning algorithm and can also be seen as a kernel neural network. The number of model parameters and test time evaluation complexity of the proposed method are O(dD) where D is the dimensionality of the input features and d is the dimension of the projection space - this is in contrast to the usual kernelization methods as, unlike them, the complexity does not scale linearly with the number of training examples. We propose a stochastic gradient based learning algorithm which makes the method scalable (w.r.t. the number of training examples), while being nonlinear. We train the method with up to half a million training pairs of 4096 dimensional CNN features. We give empirical comparisons with relevant baselines on seven challenging datasets for the task of low dimensional semantic category based image retrieval.

##### Abstract (translated by Google)
我们提出了一个新的算法的任务监督识别远距离学习非线性嵌入向量到一个低维欧氏空间。我们在具有挑战性的环境中工作，监督是在训练时对相似和不相似的对进行约束。所提出的方法是由线性马氏距离度量学习算法的近似核化导出的，也可以看作是核神经网络。所提出的方法的模型参数和测试时间评估复杂度的数量是O（dD）其中D是输入特征的维数，d是投影空间的维数 - 这与通常的核化方法相反，不同他们的复杂性并没有与训练样例的数量呈线性关系。我们提出了一种基于随机梯度的学习算法，该算法使得该方法是可伸缩的（w.r.t.训练例子的数量），同时是非线性的。我们用最多50万个4096维CNN特征的训练对训练该方法。我们对七个具有挑战性的数据集进行了基于低维语义类别的图像检索任务的经验性比较。

##### URL
[https://arxiv.org/abs/1509.08902](https://arxiv.org/abs/1509.08902)

##### PDF
[https://arxiv.org/pdf/1509.08902](https://arxiv.org/pdf/1509.08902)

