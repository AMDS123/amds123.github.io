---
layout: post
title: "What Happened to My Dog in That Network: Unraveling Top-down Generators in Convolutional Neural Networks"
date: 2015-11-23 07:48:01
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Patrick W. Gallagher, Shuai Tang, Zhuowen Tu
mathjax: true
---

* content
{:toc}

##### Abstract
Top-down information plays a central role in human perception, but plays relatively little role in many current state-of-the-art deep networks, such as Convolutional Neural Networks (CNNs). This work seeks to explore a path by which top-down information can have a direct impact within current deep networks. We explore this path by learning and using "generators" corresponding to the network internal effects of three types of transformation (each a restriction of a general affine transformation): rotation, scaling, and translation. We demonstrate how these learned generators can be used to transfer top-down information to novel settings, as mediated by the "feature flows" that the transformations (and the associated generators) correspond to inside the network. Specifically, we explore three aspects: 1) using generators as part of a method for synthesizing transformed images --- given a previously unseen image, produce versions of that image corresponding to one or more specified transformations, 2) "zero-shot learning" --- when provided with a feature flow corresponding to the effect of a transformation of unknown amount, leverage learned generators as part of a method by which to perform an accurate categorization of the amount of transformation, even for amounts never observed during training, and 3) (inside-CNN) "data augmentation" --- improve the classification performance of an existing network by using the learned generators to directly provide additional training "inside the CNN".

##### Abstract (translated by Google)
自顶向下的信息在人类感知中扮演着重要的角色，但在许多现有的最先进的深度网络（如卷积神经网络（CNN））中扮演的角色相对较少。这项工作试图探索自上而下的信息可以在当前的深层网络中产生直接影响的路径。我们通过学习和使用对应于三类转换（每个是一般的仿射变换的限制）的网络内部效应（旋转，缩放和翻译）的“发生器”来探索这个路径。我们演示了如何使用这些学习的生成器来将自上而下的信息转换为新的设置，如由网络内部的转换（和相关生成器）所对应的“特征流”所介导的。具体来说，我们探讨了三个方面：1）使用生成器作为合成变换图像的方法的一部分 - 给出先前未见的图像，生成对应于一个或多个指定变换的图像的版本，2）“零射击学习” ---如果提供了与未知量变换效果相对应的特征流，则利用学习生成器作为对变换量进行精确分类的方法的一部分，即使对于培训期间从未观察到的量， 3）（CNN内部）“数据增加” - 通过使用学习到的发生器直接提供额外的“CNN内部”培训，提高现有网络的分类性能。

##### URL
[https://arxiv.org/abs/1511.07125](https://arxiv.org/abs/1511.07125)

##### PDF
[https://arxiv.org/pdf/1511.07125](https://arxiv.org/pdf/1511.07125)

