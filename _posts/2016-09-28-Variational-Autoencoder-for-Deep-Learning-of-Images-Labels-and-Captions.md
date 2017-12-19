---
layout: post
title: "Variational Autoencoder for Deep Learning of Images, Labels and Captions"
date: 2016-09-28 15:56:15
categories: arXiv_CV
tags: arXiv_CV Caption CNN Deep_Learning
author: Yunchen Pu, Zhe Gan, Ricardo Henao, Xin Yuan, Chunyuan Li, Andrew Stevens, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
A novel variational autoencoder is developed to model images, as well as associated labels or captions. The Deep Generative Deconvolutional Network (DGDN) is used as a decoder of the latent image features, and a deep Convolutional Neural Network (CNN) is used as an image encoder; the CNN is used to approximate a distribution for the latent DGDN features/code. The latent code is also linked to generative models for labels (Bayesian support vector machine) or captions (recurrent neural network). When predicting a label/caption for a new image at test, averaging is performed across the distribution of latent codes; this is computationally efficient as a consequence of the learned CNN-based encoder. Since the framework is capable of modeling the image in the presence/absence of associated labels/captions, a new semi-supervised setting is manifested for CNN learning with images; the framework even allows unsupervised CNN learning, based on images alone.

##### Abstract (translated by Google)
一种新型的变分自动编码器被开发来模拟图像，以及相关的标签或标题。深生成去卷积网络（DGDN）被用作潜像特征的解码器，深度卷积神经网络（CNN）被用作图像编码器; CNN被用来逼近潜在的DGDN特征/代码的分布。潜在代码还与标签生成模型（贝叶斯支持向量机）或标题（循环神经网络）相关联。当在测试中预测新图像的标签/标题时，对潜在代码的分布进行平均;由于所学习的基于CNN的编码器，这在计算上是有效的。由于该框架能够在存在/不存在相关标签/标题的情况下对图像进行建模，因此新的半监督设置表现为CNN学习图像;该框架甚至允许无监督的CNN学习，仅基于图像。

##### URL
[https://arxiv.org/abs/1609.08976](https://arxiv.org/abs/1609.08976)

##### PDF
[https://arxiv.org/pdf/1609.08976](https://arxiv.org/pdf/1609.08976)

