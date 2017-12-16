---
layout: post
title: "A Deep Convolutional Auto-Encoder with Pooling - Unpooling Layers in Caffe"
date: 2017-01-18 05:24:24
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Volodymyr Turchenko, Eric Chalmers, Artur Luczak
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents the development of several models of a deep convolutional auto-encoder in the Caffe deep learning framework and their experimental evaluation on the example of MNIST dataset. We have created five models of a convolutional auto-encoder which differ architecturally by the presence or absence of pooling and unpooling layers in the auto-encoder's encoder and decoder parts. Our results show that the developed models provide very good results in dimensionality reduction and unsupervised clustering tasks, and small classification errors when we used the learned internal code as an input of a supervised linear classifier and multi-layer perceptron. The best results were provided by a model where the encoder part contains convolutional and pooling layers, followed by an analogous decoder part with deconvolution and unpooling layers without the use of switch variables in the decoder part. The paper also discusses practical details of the creation of a deep convolutional auto-encoder in the very popular Caffe deep learning framework. We believe that our approach and results presented in this paper could help other researchers to build efficient deep neural network architectures in the future.

##### Abstract (translated by Google)
本文介绍了Caffe深度学习框架下深度卷积自动编码器的几种模型的发展及其对MNIST数据集实例的实验评估。我们已经创建了五种卷积自动编码器的模型，它们在自动编码器的编码器和解码器部分中存在或不存在池层和解卷层，在架构上是不同的。我们的研究结果表明，所开发的模型在降维和无监督聚类任务方面提供了非常好的结果，并且当我们使用学习的内部代码作为监督线性分类器和多层感知器的输入时，分类错误很小。编码器部分包含卷积层和合并层的模型提供了最好的结果，接下来是类似的解码器部分，在解码器部分没有使用开关变量的解卷积和解卷层。本文还讨论了非常流行的Caffe深度学习框架中创建深卷积自动编码器的实际细节。我们相信，本文提出的方法和结果可以帮助其他研究人员在未来构建高效的深度神经网络体系结构。

##### URL
[https://arxiv.org/abs/1701.04949](https://arxiv.org/abs/1701.04949)

##### PDF
[https://arxiv.org/pdf/1701.04949](https://arxiv.org/pdf/1701.04949)

