---
layout: post
title: "Age Progression/Regression by Conditional Adversarial Autoencoder"
date: 2017-03-28 20:02:15
categories: arXiv_CV
tags: arXiv_CV Adversarial Face CNN
author: Zhifei Zhang, Yang Song, Hairong Qi
mathjax: true
---

* content
{:toc}

##### Abstract
"If I provide you a face image of mine (without telling you the actual age when I took the picture) and a large amount of face images that I crawled (containing labeled faces of different ages but not necessarily paired), can you show me what I would look like when I am 80 or what I was like when I was 5?" The answer is probably a "No." Most existing face aging works attempt to learn the transformation between age groups and thus would require the paired samples as well as the labeled query image. In this paper, we look at the problem from a generative modeling perspective such that no paired samples is required. In addition, given an unlabeled image, the generative model can directly produce the image with desired age attribute. We propose a conditional adversarial autoencoder (CAAE) that learns a face manifold, traversing on which smooth age progression and regression can be realized simultaneously. In CAAE, the face is first mapped to a latent vector through a convolutional encoder, and then the vector is projected to the face manifold conditional on age through a deconvolutional generator. The latent vector preserves personalized face features (i.e., personality) and the age condition controls progression vs. regression. Two adversarial networks are imposed on the encoder and generator, respectively, forcing to generate more photo-realistic faces. Experimental results demonstrate the appealing performance and flexibility of the proposed framework by comparing with the state-of-the-art and ground truth.

##### Abstract (translated by Google)
“如果我给你提供我的脸部图像（没有告诉你拍摄照片时的实际年龄）以及我抓取的大量脸部图像（包含不同年龄的标记脸部，但不一定配对），你能告诉我当我80岁时我会看起来像什么，或者我5岁时是什么样子？答案可能是“不”大多数现有的面部老化工作试图学习年龄组之间的转换，因此需要配对样本以及标记的查询图像。在本文中，我们从生成建模的角度来看待这个问题，从而不需要配对的样本。另外，给定一个未标记的图像，生成模型可以直接生成具有所需年龄属性的图像。我们提出了一个有条件的对抗自编码器（CAAE），学习一个人脸流形，可以同时实现平滑的年龄进展和回归。在CAAE中，首先通过卷积编码器将人脸映射到潜在向量，然后通过去卷积发生器将该向量投影到年龄为条件的人脸。潜在向量保留个性化的脸部特征（即个性），年龄条件控制进展与回归。两个对抗网络分别强加在编码器和发生器上，迫使产生更多照片般真实的面孔。实验结果表明，通过与最先进的基础事实相比较，提出的框架具有吸引人的性能和灵活性。

##### URL
[https://arxiv.org/abs/1702.08423](https://arxiv.org/abs/1702.08423)

##### PDF
[https://arxiv.org/pdf/1702.08423](https://arxiv.org/pdf/1702.08423)

