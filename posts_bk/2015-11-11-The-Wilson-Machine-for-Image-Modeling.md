---
layout: post
title: "The Wilson Machine for Image Modeling"
date: 2015-11-11 22:28:55
categories: arXiv_CV
tags: arXiv_CV CNN
author: Saeed Saremi, Terrence J. Sejnowski
mathjax: true
---

* content
{:toc}

##### Abstract
Learning the distribution of natural images is one of the hardest and most important problems in machine learning. The problem remains open, because the enormous complexity of the structures in natural images spans all length scales. We break down the complexity of the problem and show that the hierarchy of structures in natural images fuels a new class of learning algorithms based on the theory of critical phenomena and stochastic processes. We approach this problem from the perspective of the theory of critical phenomena, which was developed in condensed matter physics to address problems with infinite length-scale fluctuations, and build a framework to integrate the criticality of natural images into a learning algorithm. The problem is broken down by mapping images into a hierarchy of binary images, called bitplanes. In this representation, the top bitplane is critical, having fluctuations in structures over a vast range of scales. The bitplanes below go through a gradual stochastic heating process to disorder. We turn this representation into a directed probabilistic graphical model, transforming the learning problem into the unsupervised learning of the distribution of the critical bitplane and the supervised learning of the conditional distributions for the remaining bitplanes. We learnt the conditional distributions by logistic regression in a convolutional architecture. Conditioned on the critical binary image, this simple architecture can generate large, natural-looking images, with many shades of gray, without the use of hidden units, unprecedented in the studies of natural images. The framework presented here is a major step in bringing criticality and stochastic processes to machine learning and in studying natural image statistics.

##### Abstract (translated by Google)
学习自然图像的分布是机器学习中最困难和最重要的问题之一。问题依然存在，因为自然图像中结构的庞大复杂性涵盖了所有的长度尺度。我们分解了这个问题的复杂性，表明自然图像中的结构层次结构是基于临界现象和随机过程理论的一类新的学习算法。我们从凝聚态物理中发展起来的临界现象理论的角度来研究这个问题，以解决无限长度尺度波动的问题，并建立一个将自然图像临界性整合到学习算法中的框架。通过将图像映射到二进制图像（称为位平面）的分层结构来分解问题。在这种表示中，顶层位平面是非常关键的，在大范围内具有波动的结构。下面的位平面经历一个逐渐随机的加热过程来混乱。我们将这种表示转化为一个有向概率图形模型，将学习问题转化为关键位平面分布的无监督学习和剩余位平面的条件分布的监督式学习。我们通过逻辑回归在卷积体系中学习了条件分布。在关键的二值图像条件下，这个简单的架构可以生成大量自然的图像，具有许多灰色阴影，而不需要使用隐藏的单元，这在自然图像的研究中是前所未有的。这里介绍的框架是将关键性和随机性过程带入机器学习和研究自然图像统计的重要一步。

##### URL
[https://arxiv.org/abs/1510.07740](https://arxiv.org/abs/1510.07740)

##### PDF
[https://arxiv.org/pdf/1510.07740](https://arxiv.org/pdf/1510.07740)

