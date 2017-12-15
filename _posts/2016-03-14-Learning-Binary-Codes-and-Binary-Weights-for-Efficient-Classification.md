---
layout: post
title: "Learning Binary Codes and Binary Weights for Efficient Classification"
date: 2016-03-14 03:05:53
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification
author: Fumin Shen, Yadong Mu, Wei Liu, Yang Yang, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a generic formulation that significantly expedites the training and deployment of image classification models, particularly under the scenarios of many image categories and high feature dimensions. As a defining property, our method represents both the images and learned classifiers using binary hash codes, which are simultaneously learned from the training data. Classifying an image thereby reduces to computing the Hamming distance between the binary codes of the image and classifiers and selecting the class with minimal Hamming distance. Conventionally, compact hash codes are primarily used for accelerating image search. Our work is first of its kind to represent classifiers using binary codes. Specifically, we formulate multi-class image classification as an optimization problem over binary variables. The optimization alternatively proceeds over the binary classifiers and image hash codes. Profiting from the special property of binary codes, we show that the sub-problems can be efficiently solved through either a binary quadratic program (BQP) or linear program. In particular, for attacking the BQP problem, we propose a novel bit-flipping procedure which enjoys high efficacy and local optimality guarantee. Our formulation supports a large family of empirical loss functions and is here instantiated by exponential / hinge losses. Comprehensive evaluations are conducted on several representative image benchmarks. The experiments consistently observe reduced complexities of model training and deployment, without sacrifice of accuracies.

##### Abstract (translated by Google)
本文提出了一种通用公式，明显加快了图像分类模型的训练和部署，特别是在许多图像类别和高特征维度的场景下。作为一个定义的属性，我们的方法代表图像和学习分类使用二进制散列码，这是从训练数据同时学习。从而将图像分类归结为计算图像的二进制码和分类器之间的汉明距离，并选择具有最小汉明距离的类别。传统上，紧凑的散列码主要用于加速图像搜索。我们的工作是首次使用二进制代码来表示分类器。具体而言，我们将多类图像分类制定为二元变量的优化问题。优化可以通过二进制分类器和图像哈希码进行。利用二进制编码的特殊性质，我们证明子问题可以通过二进制二次编程（BQP）或线性编程来有效解决。具体来说，为了攻击BQP问题，我们提出了一种具有高效率和局部最优性保证的新颖的翻转过程。我们的公式支持大量的经验损失函数，在这里通过指数/铰链损失来实例化。对几个有代表性的图像基准进行综合评估。实验始终如一地观察到减少模型训练和部署的复杂性，而不牺牲准确性。

##### URL
[https://arxiv.org/abs/1603.04116](https://arxiv.org/abs/1603.04116)

##### PDF
[https://arxiv.org/pdf/1603.04116](https://arxiv.org/pdf/1603.04116)

