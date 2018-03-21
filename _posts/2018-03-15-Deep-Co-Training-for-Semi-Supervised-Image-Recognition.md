---
layout: post
title: "Deep Co-Training for Semi-Supervised Image Recognition"
date: 2018-03-15 20:13:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Deep_Learning Recognition
author: Siyuan Qiao, Wei Shen, Zhishuai Zhang, Bo Wang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of semi-supervised image recognition, which is to learn classifiers using both labeled and unlabeled images. We present Deep Co-Training, a deep learning based method inspired by the Co-Training framework. The original Co-Training learns two classifiers on two views which are data from different sources that describe the same instances. To extend this concept to deep learning, Deep Co-Training trains multiple deep neural networks to be the different views and exploits adversarial examples to encourage view difference, in order to prevent the networks from collapsing into each other. As a result, the co-trained networks provide different and complementary information about the data, which is necessary for the Co-Training framework to achieve good results. We test our method on SVHN, CIFAR-10/100 and ImageNet datasets, and our method outperforms the previous state-of-the-art methods by a large margin.

##### Abstract (translated by Google)
在本文中，我们研究半监督图像识别问题，即使用标记和未标记图像学习分类器。我们提供深度合作培训，这是一种基于联合培训框架启发的基于深度学习的方法。原始的联合培训在两个视图上学习两个分类器，这两个视图是描述相同实例的不同来源的数据。为了将这个概念延伸到深度学习，Deep Co-Training训练多个深度神经网络以形成不同的观点，并利用对抗性的例子来鼓励观点差异，以防止网络彼此崩溃。因此，联合培训网络提供了有关数据的不同补充信息，这对于共同培训框架取得良好结果是必要的。我们在SVHN，CIFAR-10/100和ImageNet数据集上测试了我们的方法，我们的方法大大优于先前的先进方法。

##### URL
[https://arxiv.org/abs/1803.05984](https://arxiv.org/abs/1803.05984)

##### PDF
[https://arxiv.org/pdf/1803.05984](https://arxiv.org/pdf/1803.05984)

