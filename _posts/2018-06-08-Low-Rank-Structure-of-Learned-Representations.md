---
layout: post
title: "Low Rank Structure of Learned Representations"
date: 2018-06-08 09:58:25
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN Image_Classification Transfer_Learning Classification
author: Amartya Sanyal, Varun Kanade, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
A key feature of neural networks, particularly deep convolutional neural networks, is their ability to "learn" useful representations from data. The very last layer of a neural network is then simply a linear model trained on these "learned" representations. Despite their numerous applications in other tasks such as classification, retrieval, clustering etc., a.k.a. transfer learning, not much work has been published that investigates the structure of these representations or indeed whether structure can be imposed on them during the training process. 
 In this paper, we study the effective dimensionality of the learned representations by models that have proved highly successful for image classification. We focus on ResNet-18, ResNet-50 and VGG-19 and observe that when trained on CIFAR10 or CIFAR100, the learned representations exhibit a fairly low rank structure. We propose a modification to the training procedure, which further encourages low rank structure on learned activations. Empirically, we show that this has implications for robustness to \emph{adversarial examples} and \emph{compression}.

##### Abstract (translated by Google)
神经网络，特别是深度卷积神经网络的一个关键特征是它们能够从数据中“学习”有用的表示。然后神经网络的最后一层就是一个线性模型，训练这些“学习”表示。尽管在诸如分类，检索，聚类等其他任务（也称为转移学习）中有许多应用，但是已经发布了很多研究调查这些表示的结构，或者确实在培训过程中是否可以对它们施加结构。
 在本文中，我们通过已经证明在图像分类中非常成功的模型来研究学习表示的有效维度。我们专注于ResNet-18，ResNet-50和VGG-19，并观察到，在CIFAR10或CIFAR100上进行培训时，学习表现呈现出相当低的排名结构。我们提出对训练程序的修改，这进一步鼓励了学习激活的低排名结构。从经验上讲，我们表明这对于\ emph {敌对示例}和\ emph {压缩}的稳健性具有影响。

##### URL
[http://arxiv.org/abs/1804.07090](http://arxiv.org/abs/1804.07090)

##### PDF
[http://arxiv.org/pdf/1804.07090](http://arxiv.org/pdf/1804.07090)

