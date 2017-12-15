---
layout: post
title: "Scene Parsing with Integration of Parametric and Non-parametric Models"
date: 2016-04-20 07:38:15
categories: arXiv_CV
tags: arXiv_CV CNN Inference Classification Prediction
author: Bing Shuai, Zhen Zuo, Gang Wang, Bing Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We adopt Convolutional Neural Networks (CNNs) to be our parametric model to learn discriminative features and classifiers for local patch classification. Based on the occurrence frequency distribution of classes, an ensemble of CNNs (CNN-Ensemble) are learned, in which each CNN component focuses on learning different and complementary visual patterns. The local beliefs of pixels are output by CNN-Ensemble. Considering that visually similar pixels are indistinguishable under local context, we leverage the global scene semantics to alleviate the local ambiguity. The global scene constraint is mathematically achieved by adding a global energy term to the labeling energy function, and it is practically estimated in a non-parametric framework. A large margin based CNN metric learning method is also proposed for better global belief estimation. In the end, the integration of local and global beliefs gives rise to the class likelihood of pixels, based on which maximum marginal inference is performed to generate the label prediction maps. Even without any post-processing, we achieve state-of-the-art results on the challenging SiftFlow and Barcelona benchmarks.

##### Abstract (translated by Google)
我们采用卷积神经网络（CNNs）作为我们的参数化模型来学习区分特征和用于局部区块分类的分类器。根据类的出现频率分布，学习CNN（CNN-Ensemble）的集合，其中每个CNN成分侧重于学习不同的和互补的视觉模式。像素的局部信仰由CNN-Ensemble输出。考虑到在本地上下文中视觉上相似的像素是不可区分的，我们利用全局场景语义来减轻局部模糊。全局场景约束是通过在标记能量函数中增加一个全局能量项而在数学上实现的，并且实际上是在非参数框架下估计的。基于CNN度量学习方法的大量边际学习也被提出用于更好的全局信念估计。最后，本地信念与全球信念的融合产生了像素的类别可能性，根据该类别的最大边际推断生成标签预测图。即使没有任何后期处理，我们在具有挑战性的SiftFlow和巴塞罗那基准测试中取得了最新的成果。

##### URL
[https://arxiv.org/abs/1604.05848](https://arxiv.org/abs/1604.05848)

##### PDF
[https://arxiv.org/pdf/1604.05848](https://arxiv.org/pdf/1604.05848)

