---
layout: post
title: "Tagger: Deep Unsupervised Perceptual Grouping"
date: 2016-11-28 18:59:28
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference Classification
author: Klaus Greff, Antti Rasmus, Mathias Berglund, Tele Hotloo Hao, Jürgen Schmidhuber, Harri Valpola
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for efficient perceptual inference that explicitly reasons about the segmentation of its inputs and features. Rather than being trained for any specific segmentation, our framework learns the grouping process in an unsupervised manner or alongside any supervised task. By enriching the representations of a neural network, we enable it to group the representations of different objects in an iterative manner. By allowing the system to amortize the iterative inference of the groupings, we achieve very fast convergence. In contrast to many other recently proposed methods for addressing multi-object scenes, our system does not assume the inputs to be images and can therefore directly handle other modalities. For multi-digit classification of very cluttered images that require texture segmentation, our method offers improved classification performance over convolutional networks despite being fully connected. Furthermore, we observe that our system greatly improves on the semi-supervised result of a baseline Ladder network on our dataset, indicating that segmentation can also improve sample efficiency.

##### Abstract (translated by Google)
我们提出了一个有效的知觉推理的框架，明确的原因关于其输入和功能的分割。我们的框架并没有经过任何特定分割的训练，而是以无监督的方式学习分组过程，或与任何监督任务一起学习。通过丰富神经网络的表示，我们使它能够以迭代的方式对不同对象的表示进行分组。通过允许系统摊分分组的迭代推理，我们实现了非常快的收敛。与许多其他最近提出的解决多物体场景的方法相比，我们的系统不会假设输入是图像，因此可以直接处理其他形式。对于需要纹理分割的非常混乱的图像的多位分类，尽管被完全连接，但是我们的方法提供了比卷积网络更好的分类性能。此外，我们观察到，我们的系统大大改善了基线梯形网络在我们的数据集上的半监督结果，表明分割也可以提高样本效率。

##### URL
[https://arxiv.org/abs/1606.06724](https://arxiv.org/abs/1606.06724)

##### PDF
[https://arxiv.org/pdf/1606.06724](https://arxiv.org/pdf/1606.06724)

