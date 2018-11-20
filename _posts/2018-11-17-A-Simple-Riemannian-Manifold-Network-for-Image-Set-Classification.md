---
layout: post
title: "A Simple Riemannian Manifold Network for Image Set Classification"
date: 2018-11-17 13:12:25
categories: arXiv_CV
tags: arXiv_CV Face Classification Deep_Learning Recognition Face_Recognition
author: Rui Wang, Xiao-Jun Wu, Josef Kittler
mathjax: true
---

* content
{:toc}

##### Abstract
In the domain of image-set based classification, a considerable advance has been made by representing original image sets as covariance matrices which typical lie in a Riemannian manifold. Specifically, it is a Symmetric Positive Definite (SPD) manifold. Traditional manifold learning methods inevitably have the property of high computational complexity or weak performance of the feature representation. In order to overcome these limitations, we propose a very simple Riemannian manifold network for image set classification. Inspired by deep learning architectures, we design a fully connected layer to generate more novel, more powerful SPD matrices. However we exploit the rectifying layer to prevent the input SPD matrices from being singular. We also introduce a non-linear learning of the proposed network with an innovative objective function. Furthermore we devise a pooling layer to further reduce the redundancy of the input SPD matrices, and the log-map layer to project the SPD manifold to the Euclidean space. For learning the connection weights between the input layer and the fully connected layer, we use Two-directional two-dimensional Principal Component Analysis ((2D)2PCA) algorithm. The proposed Riemannian manifold network (RieMNet) avoids complex computing and can be built and trained extremely easy and efficient. We have also developed a deep version of RieMNet, named as DRieMNet. The proposed RieMNet and DRieMNet are evaluated on three tasks: video-based face recognition, set-based object categorization, and set-based cell identification. Extensive experimental results show the superiority of our method over the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10628](http://arxiv.org/abs/1805.10628)

##### PDF
[http://arxiv.org/e-print/1805.10628](http://arxiv.org/e-print/1805.10628)

