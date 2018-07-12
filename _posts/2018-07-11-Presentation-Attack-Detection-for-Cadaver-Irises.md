---
layout: post
title: "Presentation Attack Detection for Cadaver Irises"
date: 2018-07-11 10:35:22
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Mateusz Trokielewicz, Adam Czajka, Piotr Maciejewicz
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a deep-learning-based method for iris presentation attack detection (PAD) when iris images are obtained from deceased people. Our approach is based on the VGG-16 architecture fine-tuned with a database of 574 post-mortem, near-infrared iris images from the Warsaw-BioBase-PostMortem-Iris-v1 database, complemented by a dataset of 256 images of live irises, collected within the scope of this study. Experiments described in this paper show that our approach is able to correctly classify iris images as either representing a live or a dead eye in almost 99% of the trials, averaged over 20 subject-disjoint, train/test splits. We also show that the post-mortem iris detection accuracy increases as time since death elapses, and that we are able to construct a classification system with APCER=0%@BPCER=1% (Attack Presentation and Bona Fide Presentation Classification Error Rates, respectively) when only post-mortem samples collected at least 16 hours post-mortem are considered. Since acquisitions of ante- and post-mortem samples differ significantly, we applied countermeasures to minimize bias in our classification methodology caused by image properties that are not related to the PAD. This included using the same iris sensor in collection of ante- and post-mortem samples, and analysis of class activation maps to ensure that discriminant iris regions utilized by our classifier are related to properties of the eye, and not to those of the acquisition protocol. This paper offers the first known to us PAD method in a post-mortem setting, together with an explanation of the decisions made by the convolutional neural network. Along with the paper we offer source codes, weights of the trained network, and a dataset of live iris images to facilitate reproducibility and further research.

##### Abstract (translated by Google)
本文提出了一种基于深度学习的虹膜表现攻击检测（PAD）方法，当从死者身上获取虹膜图像时。我们的方法基于VGG-16架构，该架构使用来自Warsaw-BioBase-PostMortem-Iris-v1数据库的574个验尸后近红外虹膜图像数据库进行微调，并辅以256张实时虹膜图像的数据集。 ，收集在本研究范围内。本文中描述的实验表明，我们的方法能够正确地将虹膜图像分类为在近99％的试验中代表活眼或死眼，平均超过20个主题不相交，训练/测试分裂。我们还表明，死后虹膜检测准确度随着死亡时间的增加而增加，并且我们能够构建一个APCER = 0％@ BPCER = 1％的分类系统（攻击演示和真实演示分类错误率分别） ）当只考虑至少16小时后收集的验尸样本时。由于前期和后期样本的采集差异很大，我们采用对策来最大限度地减少由于与PAD无关的图像属性导致的分类方法的偏差。这包括使用相同的虹膜传感器收集前期和死后样本，并分析类激活图，以确保我们的分类器使用的判别虹膜区域与眼睛的属性有关，而不是与采集协议的属性有关。 。本文提供了我们在死后环境中首次了解PAD方法，并对卷积神经网络做出的决策进行了解释。与论文一起，我们提供源代码，训练网络的权重和活虹膜图像的数据集，以促进再现性和进一步研究。

##### URL
[http://arxiv.org/abs/1807.04058](http://arxiv.org/abs/1807.04058)

##### PDF
[http://arxiv.org/pdf/1807.04058](http://arxiv.org/pdf/1807.04058)

