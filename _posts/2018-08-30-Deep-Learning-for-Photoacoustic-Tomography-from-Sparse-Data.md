---
layout: post
title: "Deep Learning for Photoacoustic Tomography from Sparse Data"
date: 2018-08-30 13:45:40
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Deep_Learning
author: Stephan Antholzer, Markus Haltmeier, Johannes Schwab
mathjax: true
---

* content
{:toc}

##### Abstract
The development of fast and accurate image reconstruction algorithms is a central aspect of computed tomography. In this paper, we investigate this issue for the sparse data problem in photoacoustic tomography (PAT). We develop a direct and highly efficient reconstruction algorithm based on deep learning. In our approach image reconstruction is performed with a deep convolutional neural network (CNN), whose weights are adjusted prior to the actual image reconstruction based on a set of training data. The proposed reconstruction approach can be interpreted as a network that uses the PAT filtered backprojection algorithm for the first layer, followed by the U-net architecture for the remaining layers. Actual image reconstruction with deep learning consists in one evaluation of the trained CNN, which does not require time consuming solution of the forward and adjoint problems. At the same time, our numerical results demonstrate that the proposed deep learning approach reconstructs images with a quality comparable to state of the art iterative approaches for PAT from sparse data.

##### Abstract (translated by Google)
快速准确的图像重建算法的发展是计算机断层扫描的核心方面。在本文中，我们研究了光声层析成像（PAT）中的稀疏数据问题。我们开发了一种基于深度学习的直接高效的重建算法。在我们的方法中，利用深度卷积神经网络（CNN）执行图像重建，其基于一组训练数据在实际图像重建之前调整其权重。所提出的重建方法可以被解释为对第一层使用PAT滤波反投影算法的网络，其后是剩余层的U-net架构。具有深度学习的实际图像重建在于对训练的CNN的一次评估，其不需要耗时地解决前向和伴随问题。同时，我们的数值结果表明，所提出的深度学习方法重建了具有与稀疏数据的PAT的现有迭代方法相当的质量的图像。

##### URL
[http://arxiv.org/abs/1704.04587](http://arxiv.org/abs/1704.04587)

##### PDF
[http://arxiv.org/pdf/1704.04587](http://arxiv.org/pdf/1704.04587)

