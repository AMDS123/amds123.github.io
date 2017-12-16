---
layout: post
title: "Disentangling Factors of Variation by Mixing Them"
date: 2017-11-20 17:00:08
categories: arXiv_CV
tags: arXiv_CV Image_Caption Knowledge Classification
author: Qiyang Hu, Attila Szabó, Tiziano Portenier, Matthias Zwicker, Paolo Favaro
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an unsupervised approach to learn image representations that consist of disentangled factors of variation. A factor of variation corresponds to an image attribute that can be discerned consistently across a set of images, such as the pose or color of objects. Our disentangled representation consists of a concatenation of feature chunks, each chunk representing a factor of variation. It supports applications such as transferring attributes from one image to another, by simply swapping feature chunks, and classification or retrieval based on one or several attributes, by considering a user specified subset of feature chunks. We learn our representation in an unsupervised manner, without any labeling or knowledge of the data domain, using an autoencoder architecture with two novel training objectives: first, we propose an invariance objective to encourage that encoding of each attribute, and decoding of each chunk, are invariant to changes in other attributes and chunks, respectively, and second, we include a classification objective, which ensures that each chunk corresponds to a consistently discernible attribute in the represented image, hence avoiding the shortcut where chunks are ignored completely. We demonstrate the effectiveness of our approach on the MNIST, Sprites, and CelebA datasets.

##### Abstract (translated by Google)
我们提出了一个无监督的方法来学习图像表示，包括解开的变异因素。变化因素对应于可以在一组图像中一致地辨别的图像属性，诸如对象的姿态或颜色。我们的解构表示由一个特征块连接组成，每个块表示一个变化因子。它通过考虑用户指定的特征块子集来支持诸如将属性从一个图像转移到另一个图像，通过简单地交换特征块以及基于一个或多个属性进行分类或检索的应用。我们以无监督的方式学习了我们的表示，没有任何数据域的标签或者知识，使用了一个自编码器结构和两个新颖的训练目标：首先，我们提出一个不变的目标来鼓励每个属性的编码和每个块的解码，对于其他属性和块的改变是不变的，其次，我们包括一个分类目标，它确保每个块对应于所表示的图像中一致可辨别的属性，从而避免块完全被忽略的捷径。我们证明了我们在MNIST，Sprites和CelebA数据集上的方法的有效性。

##### URL
[https://arxiv.org/abs/1711.07410](https://arxiv.org/abs/1711.07410)

##### PDF
[https://arxiv.org/pdf/1711.07410](https://arxiv.org/pdf/1711.07410)

