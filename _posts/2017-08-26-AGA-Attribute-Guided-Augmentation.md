---
layout: post
title: "AGA: Attribute Guided Augmentation"
date: 2017-08-26 19:52:46
categories: arXiv_CV
tags: arXiv_CV Knowledge Recognition
author: Mandar Dixit, Roland Kwitt, Marc Niethammer, Nuno Vasconcelos
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of data augmentation, i.e., generating artificial samples to extend a given corpus of training data. Specifically, we propose attributed-guided augmentation (AGA) which learns a mapping that allows to synthesize data such that an attribute of a synthesized sample is at a desired value or strength. This is particularly interesting in situations where little data with no attribute annotation is available for learning, but we have access to a large external corpus of heavily annotated samples. While prior works primarily augment in the space of images, we propose to perform augmentation in feature space instead. We implement our approach as a deep encoder-decoder architecture that learns the synthesis function in an end-to-end manner. We demonstrate the utility of our approach on the problems of (1) one-shot object recognition in a transfer-learning setting where we have no prior knowledge of the new classes, as well as (2) object-based one-shot scene recognition. As external data, we leverage 3D depth and pose information from the SUN RGB-D dataset. Our experiments show that attribute-guided augmentation of high-level CNN features considerably improves one-shot recognition performance on both problems.

##### Abstract (translated by Google)
我们考虑数据增强的问题，即产生人工样本以扩展给定的训练数据的语料库。具体而言，我们提出归因引导增强（AGA），其学习允许合成数据的映射，使得合成样本的属性处于期望的值或强度。在没有任何属性注释的小数据不可用于学习的情况下，这是特别有趣的，但是我们可以访问大量外部注解样本的语料库。虽然先前的工作主要是在图像空间中增加，但我们建议在特征空间中进行增强。我们将这种方法作为一种深入的编码器 - 解码器架构来实现，以一种端到端的方式学习综合功能。我们证明了我们的方法在以下问题上的效用：（1）在转移学习设置中的一次性对象识别，其中我们没有对新类别的先验知识，以及（2）基于对象的一次性场景识别。作为外部数据，我们利用SUN RGB-D数据集的3D深度和姿态信息。我们的实验表明，高级CNN特征的属性引导增强显着提高了对这两个问题的一次性识别性能。

##### URL
[https://arxiv.org/abs/1612.02559](https://arxiv.org/abs/1612.02559)

##### PDF
[https://arxiv.org/pdf/1612.02559](https://arxiv.org/pdf/1612.02559)

