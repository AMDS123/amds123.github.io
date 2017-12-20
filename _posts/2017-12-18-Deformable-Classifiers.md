---
layout: post
title: "Deformable Classifiers"
date: 2017-12-18 23:12:06
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Jiajun Shen, Yali Amit
mathjax: true
---

* content
{:toc}

##### Abstract
Geometric variations of objects, which do not modify the object class, pose a major challenge for object recognition. These variations could be rigid as well as non-rigid transformations. In this paper, we design a framework for training deformable classifiers, where latent transformation variables are introduced, and a transformation of the object image to a reference instantiation is computed in terms of the classifier output, separately for each class. The classifier outputs for each class, after transformation, are compared to yield the final decision. As a by-product of the classification this yields a transformation of the input object to a reference pose, which can be used for downstream tasks such as the computation of object support. We apply a two-step training mechanism for our framework, which alternates between optimizing over the latent transformation variables and the classifier parameters to minimize the loss function. We show that multilayer perceptrons, also known as deep networks, are well suited for this approach and achieve state of the art results on the rotated MNIST and the Google Earth dataset, and produce competitive results on MNIST and CIFAR-10 when training on smaller subsets of training data.

##### Abstract (translated by Google)
对象的几何变化不会修改对象类别，这是对象识别的一个主要挑战。这些变化可能是刚性的，也可能是非刚性的变化。在本文中，我们设计了一个用于训练可变形分类器的框架，其中引入了潜在的变换变量，并且根据分类器输出将对象图像转换为参考实例化。每个类的分类器输出在转换之后进行比较以产生最终的决定。作为分类的副产品，这产生输入对象到参考姿态的变换，其可以用于下游任务，诸如对象支持的计算。我们为我们的框架应用了一个两步训练机制，在潜在的转换变量和分类器参数之间交替优化，以使损失函数最小化。我们表明，多层感知器，也被称为深网络，非常适合这种方法，并实现旋转MNIST和谷歌地球数据集上的最先进的结果，并在MNIST和CIFAR-10上产生有竞争力的结果时，在较小的子集的训练数据。

##### URL
[http://arxiv.org/abs/1712.06715](http://arxiv.org/abs/1712.06715)

##### PDF
[http://arxiv.org/pdf/1712.06715](http://arxiv.org/pdf/1712.06715)

