---
layout: post
title: "Semi-Supervised Hierarchical Semantic Object Parsing"
date: 2017-10-29 16:24:53
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Jalal Mirakhorli, Hamidreza Amindavar
mathjax: true
---

* content
{:toc}

##### Abstract
Models based on Convolutional Neural Networks (CNNs) have been proven very successful for semantic segmentation and object parsing that yield hierarchies of features. Our key insight is to build convolutional networks that take input of arbitrary size and produce object parsing output with efficient inference and learning. In this work, we focus on the task of instance segmentation and parsing which recognizes and localizes objects down to a pixel level base on deep CNN. Therefore, unlike some related work, a pixel cannot belong to multiple instances and parsing. Our model is based on a deep neural network trained for object masking that supervised with input image and follow incorporates a Conditional Random Field (CRF) with end-to-end trainable piecewise order potentials based on object parsing outputs. In each CRF unit we designed terms to capture the short range and long range dependencies from various neighbors. The accurate instance-level segmentation that our network produce is reflected by the considerable improvements obtained over previous work at high APr thresholds. We demonstrate the effectiveness of our model with extensive experiments on challenging dataset subset of PASCAL VOC2012.

##### Abstract (translated by Google)
基于卷积神经网络（CNN）的模型已经被证明是非常成功的语义分割和对象分析，产生功能的层次结构。我们的主要观点是建立卷积网络，以任意大小的输入和生成对象解析输出，并进行有效的推理和学习。在这项工作中，我们把重点放在实例分割和分析的任务上，这个任务根据深CNN将对象识别和定位到像素级。因此，不像一些相关的工作，像素不能属于多个实例和解析。我们的模型是基于深度神经网络训练的对象掩蔽，监督输入图像，并遵循条件随机场（CRF）与端到端可训练的分段序电位基于对象分析输出结合。在每个CRF单元中，我们设计了一些术语来捕捉来自不同邻居的短程和长程相关性。我们的网络所产生的准确的实例级分割反映了在高APr阈值下相对于以前的工作获得的显着改进。我们展示了我们的模型的有效性，在PASCAL VOC2012具有挑战性的数据集子集上进行了广泛的实验。

##### URL
[https://arxiv.org/abs/1709.08019](https://arxiv.org/abs/1709.08019)

##### PDF
[https://arxiv.org/pdf/1709.08019](https://arxiv.org/pdf/1709.08019)

