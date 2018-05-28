---
layout: post
title: "Pooling is neither necessary nor sufficient for appropriate deformation stability in CNNs"
date: 2018-05-25 13:03:50
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Avraham Ruderman, Neil C. Rabinowitz, Ari S. Morcos, Daniel Zoran
mathjax: true
---

* content
{:toc}

##### Abstract
Many of our core assumptions about how neural networks operate remain empirically untested. One common assumption is that convolutional neural networks need to be stable to small translations and deformations to solve image recognition tasks. For many years, this stability was baked into CNN architectures by incorporating interleaved pooling layers. Recently, however, interleaved pooling has largely been abandoned. This raises a number of questions: Are our intuitions about deformation stability right at all? Is it important? Is pooling necessary for deformation invariance? If not, how is deformation invariance achieved in its absence? In this work, we rigorously test these questions, and find that deformation stability in convolutional networks is more nuanced than it first appears: (1) Deformation invariance is not a binary property, but rather that different tasks require different degrees of deformation stability at different layers. (2) Deformation stability is not a fixed property of a network and is heavily adjusted over the course of training, largely through the smoothness of the convolutional filters. (3) Interleaved pooling layers are neither necessary nor sufficient for achieving the optimal form of deformation stability for natural image classification. (4) Pooling confers too much deformation stability for image classification at initialization, and during training, networks have to learn to counteract this inductive bias. Together, these findings provide new insights into the role of interleaved pooling and deformation invariance in CNNs, and demonstrate the importance of rigorous empirical testing of even our most basic assumptions about the working of neural networks.

##### Abstract (translated by Google)
我们关于神经网络如何运作的许多核心假设仍未经验证。一个常见的假设是卷积神经网络需要对小的平移和变形稳定以解决图像识别任务。多年以来，这种稳定性通过结合交错池化层而被纳入到CNN架构中。然而，最近，交错式联营在很大程度上已被放弃。这引发了许多问题：我们对变形稳定性的直觉是否正确？是不是重要？为变形不变性所需的池吗？如果不是，那么在不存在时如何实现变形不变性？在这项工作中，我们对这些问题进行了严格测试，发现卷积网络中的变形稳定性比第一次出现时更加细致：（1）变形不变性不是二元性质，而是不同任务需要不同程度的变形稳定性层。 （2）变形稳定性不是网络的固定属性，并且在训练过程中进行了大量调整，主要是通过卷积滤波器的平滑性。 （3）为实现自然图像分类的最佳形变稳定性，交织池层既不必要也不足够。 （4）池在初始化时赋予图像分类太多的变形稳定性，并且在训练期间，网络必须学会抵消这种感应偏差。总之，这些发现提供了有关CNNs中交错汇集和变形不变性的作用的新见解，并且证明了甚至是关于神经网络工作的最基本假设的严格实证测试的重要性。

##### URL
[http://arxiv.org/abs/1804.04438](http://arxiv.org/abs/1804.04438)

##### PDF
[http://arxiv.org/pdf/1804.04438](http://arxiv.org/pdf/1804.04438)

