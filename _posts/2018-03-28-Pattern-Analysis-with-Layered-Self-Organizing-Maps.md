---
layout: post
title: "Pattern Analysis with Layered Self-Organizing Maps"
date: 2018-03-28 17:07:18
categories: arXiv_CV
tags: arXiv_CV GAN Image_Generation CNN Classification
author: David Friedlander
mathjax: true
---

* content
{:toc}

##### Abstract
This paper defines a new learning architecture, Layered Self-Organizing Maps (LSOMs), that uses the SOM and supervised-SOM learning algorithms. The architecture is validated with the MNIST database of hand-written digit images. LSOMs are similar to convolutional neural nets (covnets) in the way they sample data, but different in the way they represent features and learn. LSOMs analyze (or generate) image patches with maps of exemplars determined by the SOM learning algorithm rather than feature maps from filter-banks learned via backprop. LSOMs provide an alternative to features derived from covnets. Multi-layer LSOMs are trained bottom-up, without the use of backprop and therefore may be of interest as a model of the visual cortex. The results show organization at multiple levels. The algorithm appears to be resource efficient in learning, classifying and generating images. Although LSOMs can be used for classification, their validation accuracy for these exploratory runs was well below the state of the art. The goal of this article is to define the architecture and display the structures resulting from its application to the MNIST images.

##### Abstract (translated by Google)
本文定义了一种新的学习架构，分层自组织映射（LSOMs），它使用了SOM和监督式SOM学习算法。该架构通过手写数字图像的MNIST数据库进行验证。 LSOM在采样数据的方式上与卷积神经网络（covnets）相似，但它们代表特征和学习的方式不同。 LSOM使用SOM学习算法确定的示例地图来分析（或生成）图像块，而不是通过backprop学习的滤波器组的特征图。 LSOM提供了从covnets派生的特征的替代方案。多层LSOM经过自下而上的训练，不需要使用backprop，因此可能作为视觉皮层的模型而感兴趣。结果显示了多层次的组织。该算法似乎在学习，分类和生成图像方面具有资源高效性。虽然LSOM可用于分类，但它们对这些探索性运行的验证准确度远低于现有技术水平。本文的目标是定义体系结构，并将其应用所产生的结构显示给MNIST图像。

##### URL
[https://arxiv.org/abs/1803.08996](https://arxiv.org/abs/1803.08996)

##### PDF
[https://arxiv.org/pdf/1803.08996](https://arxiv.org/pdf/1803.08996)

