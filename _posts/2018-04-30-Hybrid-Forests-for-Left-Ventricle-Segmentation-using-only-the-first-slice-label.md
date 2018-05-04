---
layout: post
title: "Hybrid Forests for Left Ventricle Segmentation using only the first slice label"
date: 2018-04-30 16:43:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Ismaël Koné, Lahsen Boulmane
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning models produce state-of-the-art results in many MRI images segmentation. However, most of these models are trained on very large datasets which come from experts manual labeling. This labeling process is very time consuming and costs experts work. Therefore finding a way to reduce this cost is on high demand. In this paper, we propose a segmentation method which exploits MRI images sequential structure to nearly drop out this labeling task. Only the first slice needs to be manually labeled to train the model which then infers the next slice's segmentation. Inference result is another datum used to train the model again. The updated model then infers the third slice and the same process is carried out until the last slice. The proposed model is an combination of two Random Forest algorithms: the classical one and a recent one namely Mondrian Forests. We applied our method on human left ventricle segmentation and results are very promising. This method can also be used to generate labels.

##### Abstract (translated by Google)
机器学习模型在许多MRI图像分割中产生了最新的结果。但是，大多数这些模型都是在来自专家手动标记的非常大的数据集上进行培训的。这个标签制作过程非常耗时，而且专家的成本也很高。因此寻求一种降低成本的方法是高需求的。在本文中，我们提出了一种利用MRI图像序列结构的分割方法，几乎​​剔除了这个标记任务。只有第一个切片需要手动标记以训练模型，然后推断下一个切片的分割。推断结果是用于再次训练模型的另一个数据。然后更新后的模型推断第三个切片，并执行相同的过程直到最后一个切片。所提出的模型是两种随机森林算法的组合：经典算法和最近的一种，即Mondrian森林。我们将该方法应用于人体左心室分割，结果非常有前景。这种方法也可以用来生成标签。

##### URL
[https://arxiv.org/abs/1804.11317](https://arxiv.org/abs/1804.11317)

##### PDF
[https://arxiv.org/pdf/1804.11317](https://arxiv.org/pdf/1804.11317)

