---
layout: post
title: "Robust Spatial Filtering with Graph Convolutional Neural Networks"
date: 2017-07-14 19:57:57
categories: arXiv_CV
tags: arXiv_CV GAN CNN Classification Recognition
author: Felipe Petroski Such, Shagan Sah, Miguel Dominguez, Suhas Pillai, Chao Zhang, Andrew Michael, Nathan Cahill, Raymond Ptucha
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have recently led to incredible breakthroughs on a variety of pattern recognition problems. Banks of finite impulse response filters are learned on a hierarchy of layers, each contributing more abstract information than the previous layer. The simplicity and elegance of the convolutional filtering process makes them perfect for structured problems such as image, video, or voice, where vertices are homogeneous in the sense of number, location, and strength of neighbors. The vast majority of classification problems, for example in the pharmaceutical, homeland security, and financial domains are unstructured. As these problems are formulated into unstructured graphs, the heterogeneity of these problems, such as number of vertices, number of connections per vertex, and edge strength, cannot be tackled with standard convolutional techniques. We propose a novel neural learning framework that is capable of handling both homogeneous and heterogeneous data, while retaining the benefits of traditional CNN successes. Recently, researchers have proposed variations of CNNs that can handle graph data. In an effort to create learnable filter banks of graphs, these methods either induce constraints on the data or require preprocessing. As opposed to spectral methods, our framework, which we term Graph-CNNs, defines filters as polynomials of functions of the graph adjacency matrix. Graph-CNNs can handle both heterogeneous and homogeneous graph data, including graphs having entirely different vertex or edge sets. We perform experiments to validate the applicability of Graph-CNNs to a variety of structured and unstructured classification problems and demonstrate state-of-the-art results on document and molecule classification problems.

##### Abstract (translated by Google)
卷积神经网络（CNN）最近在各种模式识别问题上取得了令人难以置信的突破。有限脉冲响应滤波器组是在层次层次上学习的，每个层次比前一层次贡献更多的抽象信息。卷积滤波过程的简单性和高雅性使得它们适用于图像，视频或语音等结构化问题，其中顶点在邻居的数量，位置和强度方面是均匀的。绝大多数分类问题，例如制药，国土安全和金融领域都是非结构化的。由于这些问题都是用非结构化的图形表示的，所以这些问题的不一致性，比如顶点的数量，每个顶点的连接数量和边缘强度，都不能用标准的卷积技术来解决。我们提出了一种新颖的神经学习框架，能够同时处理同质和异构数据，同时保留传统CNN成功的好处。最近，研究人员提出了可以处理图形数据的CNN变体。为了创建可学习的图的滤波器组，这些方法或者引起对数据的约束或者需要预处理。与光谱方法相反，我们称之为Graph-CNNs的框架将滤波器定义为图邻接矩阵函数的多项式。图形CNN可以处理异构和同类图形数据，包括具有完全不同的顶点或边集的图形。我们进行实验来验证Graph-CNN对各种结构化和非结构化分类问题的适用性，并展示关于文档和分子分类问题的最新结果。

##### URL
[https://arxiv.org/abs/1703.00792](https://arxiv.org/abs/1703.00792)

##### PDF
[https://arxiv.org/pdf/1703.00792](https://arxiv.org/pdf/1703.00792)

