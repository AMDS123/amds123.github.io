---
layout: post
title: "Efficient softmax approximation for GPUs"
date: 2017-06-19 16:33:04
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Edouard Grave, Armand Joulin, Moustapha Cissé, David Grangier, Hervé Jégou
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approximate strategy to efficiently train neural network based language models over very large vocabularies. Our approach, called adaptive softmax, circumvents the linear dependency on the vocabulary size by exploiting the unbalanced word distribution to form clusters that explicitly minimize the expectation of computation time. Our approach further reduces the computational time by exploiting the specificities of modern architectures and matrix-matrix vector operations, making it particularly suited for graphical processing units. Our experiments carried out on standard benchmarks, such as EuroParl and One Billion Word, show that our approach brings a large gain in efficiency over standard approximations while achieving an accuracy close to that of the full softmax. The code of our method is available at this https URL

##### Abstract (translated by Google)
我们提出了一个近似的策略，以在非常大的词汇表上有效地训练基于神经网络的语言模型。我们的方法称为自适应softmax，通过利用不平衡的单词分布来形成群集，从而避免了对词汇大小的线性依赖，从而明确地将计算时间的期望最小化。我们的方法通过利用现代体系结构和矩阵向量操作的特性进一步减少了计算时间，使其特别适合于图形处理单元。我们在EuroParl和One Billion Word等标准基准上进行的实验表明，与标准逼近相比，我们的方法在效率方面带来了巨大的提高，同时达到了接近完全softmax的精度。我们的方法的代码在这个https URL上可用

##### URL
[https://arxiv.org/abs/1609.04309](https://arxiv.org/abs/1609.04309)

##### PDF
[https://arxiv.org/pdf/1609.04309](https://arxiv.org/pdf/1609.04309)

