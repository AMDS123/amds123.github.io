---
layout: post
title: "Deep Representation Learning for Domain Adaptation of Semantic Image Segmentation"
date: 2018-05-10 19:14:06
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Transfer_Learning Semantic_Segmentation Represenation_Learning
author: Assia Benbihi, Matthieu Geist, C&#xe9;dric Pradalier
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks have pushed the state-of-the art for semantic segmentation provided that a large amount of images together with pixel-wise annotations is available. Data collection is expensive and a solution to alleviate it is to use transfer learning. This reduces the amount of annotated data required for the network training but it does not get rid of this heavy processing step. We propose a method of transfer learning without annotations on the target task for datasets with redundant content and distinct pixel distributions. Our method takes advantage of the approximate content alignment of the images between two datasets when the approximation error prevents the reuse of annotation from one dataset to another. Given the annotations for only one dataset, we train a first network in a supervised manner. This network autonomously learns to generate deep data representations relevant to the semantic segmentation. Then the images in the new dataset, we train a new network to generate a deep data representation that matches the one from the first network on the previous dataset. The training consists in a regression between feature maps and does not require any annotations on the new dataset. We show that this method reaches performances similar to a classic transfer learning on the PASCAL VOC dataset with synthetic transformations.

##### Abstract (translated by Google)
深卷积神经网络推动了语义分割技术的发展，只要有大量的图像和像素方式的注释一起使用。数据收集是昂贵的，并且减轻它的一个解决方案是使用转移学习。这减少了网络培训所需的注释数据量，但并没有摆脱这一繁重的处理步骤。我们提出了一种转移学习的方法，对于具有冗余内容和不同像素分布的数据集的目标任务没有注释。当近似误差阻止从一个数据集到另一个数据集的注释重用时，我们的方法利用了两个数据集之间图像的近似内容对齐。鉴于只有一个数据集的注释，我们以监督的方式训练第一个网络。该网络自主学习生成与语义分割相关的深度数据表示。然后在新数据集中的图像，我们训练一个新的网络，以生成一个深度数据表示，以匹配前一个数据集上第一个网络的数据。训练包括特征映射之间的回归，并且不需要对新数据集进行任何注释。我们证明这种方法的性能类似于PASCAL VOC数据集上的经典转换学习，并且具有合成转换。

##### URL
[http://arxiv.org/abs/1805.04141](http://arxiv.org/abs/1805.04141)

##### PDF
[http://arxiv.org/pdf/1805.04141](http://arxiv.org/pdf/1805.04141)

