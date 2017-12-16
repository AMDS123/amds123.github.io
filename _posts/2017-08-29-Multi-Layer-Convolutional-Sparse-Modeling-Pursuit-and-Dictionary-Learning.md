---
layout: post
title: "Multi-Layer Convolutional Sparse Modeling: Pursuit and Dictionary Learning"
date: 2017-08-29 11:43:40
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Jeremias Sulam, Vardan Papyan, Yaniv Romano, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
The recently proposed Multi-Layer Convolutional Sparse Coding (ML-CSC) model, consisting of a cascade of convolutional sparse layers, provides a new interpretation of Convolutional Neural Networks (CNNs). Under this framework, the computation of the forward pass in a CNN is equivalent to a pursuit algorithm aiming to estimate the nested sparse representation vectors -- or feature maps -- from a given input signal. Despite having served as a pivotal connection between CNNs and sparse modeling, a deeper understanding of the ML-CSC is still lacking: there are no pursuit algorithms that can serve this model exactly, nor are there conditions to guarantee a non-empty model. While one can easily obtain signals that approximately satisfy the ML-CSC constraints, it remains unclear how to simply sample from the model and, more importantly, how one can train the convolutional filters from real data. In this work, we propose a sound pursuit algorithm for the ML-CSC model by adopting a projection approach. We provide new and improved bounds on the stability of the solution of such pursuit and we analyze different practical alternatives to implement this in practice. We show that the training of the filters is essential to allow for non-trivial signals in the model, and we derive an online algorithm to learn the dictionaries from real data, effectively resulting in cascaded sparse convolutional layers. Last, but not least, we demonstrate the applicability of the ML-CSC model for several applications in an unsupervised setting, providing competitive results. Our work represents a bridge between matrix factorization, sparse dictionary learning and sparse auto-encoders, and we analyze these connections in detail.

##### Abstract (translated by Google)
最近提出的多层卷积稀疏编码（ML-CSC）的模式，由卷积疏层的级联，提供卷积神经网络（细胞神经网络）的全新诠释。在此框架下，在一个CNN直传的计算等同于追踪算法旨在估计嵌套稀疏表示矢量 - 从给定的输入信号 - 或特征地图。尽管曾担任细胞神经网络和稀疏的造型，ML-CSC有更深的了解仍然缺乏之间的枢轴连接：有没有追求算法，可以准确地服务于这种模式，也没有条件，以保证非空模型。尽管人们可以容易地获得大致满足ML-CSC约束的信号，它仍不清楚如何简单地从模型采样和，更重要的是，一个如何从实际数据训练卷积滤波器。在这项工作中，我们通过采用投影方法提出了ML-CSC模型的健全追踪算法。我们对这种追求的解决方案的稳定性提供了新的和改进的界限，我们分析了不同的实际替代方案来实现这一点。我们发现，过滤器的培训是必不可少的，允许在模型中不平凡的信号，我们得出一个在线算法学习从实际数据字典，有效地产生级联稀疏卷积层。最后但并非最不重要的是，我们证明了ML-CSC模型在无监督环境中的几种应用的适用性，提供了有竞争力的结果。我们的工作代表矩阵分解，稀疏字典学习和稀疏自动编码器之间的桥梁，我们详细分析这些连接。

##### URL
[https://arxiv.org/abs/1708.08705](https://arxiv.org/abs/1708.08705)

##### PDF
[https://arxiv.org/pdf/1708.08705](https://arxiv.org/pdf/1708.08705)

