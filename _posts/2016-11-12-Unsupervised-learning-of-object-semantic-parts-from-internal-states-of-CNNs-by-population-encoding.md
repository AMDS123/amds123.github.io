---
layout: post
title: "Unsupervised learning of object semantic parts from internal states of CNNs by population encoding"
date: 2016-11-12 13:37:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Classification Detection
author: Jianyu Wang, Zhishuai Zhang, Cihang Xie, Vittal Premachandran, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
We address the key question of how object part representations can be found from the internal states of CNNs that are trained for high-level tasks, such as object classification. This work provides a new unsupervised method to learn semantic parts and gives new understanding of the internal representations of CNNs. Our technique is based on the hypothesis that semantic parts are represented by populations of neurons rather than by single filters. We propose a clustering technique to extract part representations, which we call Visual Concepts. We show that visual concepts are semantically coherent in that they represent semantic parts, and visually coherent in that corresponding image patches appear very similar. Also, visual concepts provide full spatial coverage of the parts of an object, rather than a few sparse parts as is typically found in keypoint annotations. Furthermore, We treat single visual concept as part detector and evaluate it for keypoint detection using the PASCAL3D+ dataset and for part detection using our newly annotated ImageNetPart dataset. The experiments demonstrate that visual concepts can be used to detect parts. We also show that some visual concepts respond to several semantic parts, provided these parts are visually similar. Thus visual concepts have the essential properties: semantic meaning and detection capability. Note that our ImageNetPart dataset gives rich part annotations which cover the whole object, making it useful for other part-related applications.

##### Abstract (translated by Google)
我们解决的关键问题是如何从CNN的内部状态中找到对象分类表示，这些内部状态是经过高级任务（如对象分类）训练的。这项工作提供了一种新的无监督方法来学习语义部分，并对CNN的内部表示形式有了新的认识。我们的技术是基于这样的假设，即语义部分是由神经元群体而不是单个过滤器来表示的。我们提出一种聚类技术来提取部分表示，我们称之为Visual Concepts。我们表明，视觉概念在语义上是连贯的，因为它们表示语义部分，并且在视觉上相关，相应的图像块显得非常相似。而且，视觉概念提供了对象部分的全部空间覆盖，而不是像关键点注释中通常所见的那样稀疏的部分。此外，我们将单个视觉概念作为部分检测器进行处理，并使用PASCAL3D +数据集对其进行关键点检测，并使用新注释的ImageNetPart数据集进行部分检测。实验表明，视觉概念可以用来检测零件。我们还表明，一些视觉概念响应几个语义部分，只要这些部分在视觉上相似。因此，视觉概念具有基本属性：语义和检测能力。请注意，我们的ImageNetPart数据集提供了丰富的部分注释，覆盖整个对象，使其对其他部分相关的应用程序非常有用。

##### URL
[https://arxiv.org/abs/1511.06855](https://arxiv.org/abs/1511.06855)

##### PDF
[https://arxiv.org/pdf/1511.06855](https://arxiv.org/pdf/1511.06855)

