---
layout: post
title: "Graph Based Convolutional Neural Network"
date: 2016-09-28 15:32:59
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Deep_Learning
author: Michael Edwards, Xianghua Xie
mathjax: true
---

* content
{:toc}

##### Abstract
The benefit of localized features within the regular domain has given rise to the use of Convolutional Neural Networks (CNNs) in machine learning, with great proficiency in the image classification. The use of CNNs becomes problematic within the irregular spatial domain due to design and convolution of a kernel filter being non-trivial. One solution to this problem is to utilize graph signal processing techniques and the convolution theorem to perform convolutions on the graph of the irregular domain to obtain feature map responses to learnt filters. We propose graph convolution and pooling operators analogous to those in the regular domain. We also provide gradient calculations on the input data and spectral filters, which allow for the deep learning of an irregular spatial domain problem. Signal filters take the form of spectral multipliers, applying convolution in the graph spectral domain. Applying smooth multipliers results in localized convolutions in the spatial domain, with smoother multipliers providing sharper feature maps. Algebraic Multigrid is presented as a graph pooling method, reducing the resolution of the graph through agglomeration of nodes between layers of the network. Evaluation of performance on the MNIST digit classification problem in both the regular and irregular domain is presented, with comparison drawn to standard CNN. The proposed graph CNN provides a deep learning method for the irregular domains present in the machine learning community, obtaining 94.23% on the regular grid, and 94.96% on a spatially irregular subsampled MNIST.

##### Abstract (translated by Google)
常规域内的局部化特征的优点已经引起在机器学习中使用卷积神经网络（CNN），并且在图像分类方面具有很高的精度。由于内核滤波器的设计和卷积是非平凡的，因此CNN的使用在不规则的空间域内成为问题。解决这个问题的一个办法是利用图形信号处理技术和卷积定理对不规则域的图形进行卷积，以获得对学习滤波器的特征映射。我们提出类似于常规域中的图的卷积和合并算子。我们还提供了输入数据和光谱过滤器的梯度计算，可以深入学习不规则的空间域问题。信号滤波器采用谱乘法器的形式，在图谱域中应用卷积。应用平滑的乘法器会导致空间域中的局部卷积，使用平滑的乘法器提供更加清晰的特征映射。代数多重网格作为一种图形化的方法呈现，通过网络层间节点的聚集来降低图形的分辨率。介绍了对MNIST数字分类问题在正规和非正规领域的性能评价，并与标准CNN进行了比较。提出的图CNN为机器学习领域中存在的不规则域提供了一种深度学习方法，在规则网格上获得了94.23％，在空间不规则子采样MNIST上获得了94.96％。

##### URL
[https://arxiv.org/abs/1609.08965](https://arxiv.org/abs/1609.08965)

##### PDF
[https://arxiv.org/pdf/1609.08965](https://arxiv.org/pdf/1609.08965)

