---
layout: post
title: "Multi-Layer Convolutional Sparse Modeling: Pursuit and Dictionary Learning"
date: 2018-06-30 19:46:15
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Jeremias Sulam, Vardan Papyan, Yaniv Romano, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
The recently proposed Multi-Layer Convolutional Sparse Coding (ML-CSC) model, consisting of a cascade of convolutional sparse layers, provides a new interpretation of Convolutional Neural Networks (CNNs). Under this framework, the computation of the forward pass in a CNN is equivalent to a pursuit algorithm aiming to estimate the nested sparse representation vectors -- or feature maps -- from a given input signal. Despite having served as a pivotal connection between CNNs and sparse modeling, a deeper understanding of the ML-CSC is still lacking: there are no pursuit algorithms that can serve this model exactly, nor are there conditions to guarantee a non-empty model. While one can easily obtain signals that approximately satisfy the ML-CSC constraints, it remains unclear how to simply sample from the model and, more importantly, how one can train the convolutional filters from real data. 
 In this work, we propose a sound pursuit algorithm for the ML-CSC model by adopting a projection approach. We provide new and improved bounds on the stability of the solution of such pursuit and we analyze different practical alternatives to implement this in practice. We show that the training of the filters is essential to allow for non-trivial signals in the model, and we derive an online algorithm to learn the dictionaries from real data, effectively resulting in cascaded sparse convolutional layers. Last, but not least, we demonstrate the applicability of the ML-CSC model for several applications in an unsupervised setting, providing competitive results. Our work represents a bridge between matrix factorization, sparse dictionary learning and sparse auto-encoders, and we analyze these connections in detail.

##### Abstract (translated by Google)
最近提出的多层卷积稀疏编码（ML-CSC）模型由卷积稀疏层级联组成，为卷积神经网络（CNN）提供了新的解释。在该框架下，CNN中的前向通道的计算等效于旨在从给定输入信号估计嵌套稀疏表示向量（或特征图）的追踪算法。尽管已经成为CNN和稀疏建模之间的关键连接，但仍然缺乏对ML-CSC的更深入理解：没有追求算法可以准确地服务于该模型，也没有条件来保证非空模型。虽然人们可以很容易地获得大致满足ML-CSC约束的信号，但仍然不清楚如何从模型中简单地采样，更重要的是，如何从真实数据中训练卷积滤波器。
 在这项工作中，我们采用投影方法为ML-CSC模型提出了一种声音追踪算法。我们为这种追求的解决方案的稳定性提供了新的和改进的界限，并且我们分析了在实践中实现这一点的不同实际替代方案。我们证明了滤波器的训练对于允许模型中的非平凡信号是必不可少的，并且我们推导出在线算法以从真实数据中学习字典，从而有效地产生级联的稀疏卷积层。最后，但并非最不重要的是，我们证明了ML-CSC模型在无监督环境中的几种应用的适用性，提供了有竞争力的结果。我们的工作代表了矩阵分解，稀疏字典学习和稀疏自动编码器之间的桥梁，我们详细分析了这些连接。

##### URL
[http://arxiv.org/abs/1708.08705](http://arxiv.org/abs/1708.08705)

##### PDF
[http://arxiv.org/pdf/1708.08705](http://arxiv.org/pdf/1708.08705)

