---
layout: post
title: "Semantic Image Retrieval via Active Grounding of Visual Situations"
date: 2017-10-31 20:15:49
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Relation
author: Max H. Quinn, Erik Conser, Jordan M. Witte, Melanie Mitchell
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a novel architecture for semantic image retrieval---in particular, retrieval of instances of visual situations. Visual situations are concepts such as "a boxing match," "walking the dog," "a crowd waiting for a bus," or "a game of ping-pong," whose instantiations in images are linked more by their common spatial and semantic structure than by low-level visual similarity. Given a query situation description, our architecture---called Situate---learns models capturing the visual features of expected objects as well the expected spatial configuration of relationships among objects. Given a new image, Situate uses these models in an attempt to ground (i.e., to create a bounding box locating) each expected component of the situation in the image via an active search procedure. Situate uses the resulting grounding to compute a score indicating the degree to which the new image is judged to contain an instance of the situation. Such scores can be used to rank images in a collection as part of a retrieval system. In the preliminary study described here, we demonstrate the promise of this system by comparing Situate's performance with that of two baseline methods, as well as with a related semantic image-retrieval system based on "scene graphs."

##### Abstract (translated by Google)
我们描述了一种新颖的用于语义图像检索的体系结构 - 特别是检索视觉情况的实例。视觉情境是指“拳击比赛”，“走路的狗”，“等待公车的人群”或“乒乓游戏”等概念，其图像中的实例更多地通过其共同的空间和语义结构比低层次的视觉相似。给定一个查询情况的描述，我们的架构称为状态 - 学习模型捕获预期对象的视觉特征以及对象之间关系的预期空间配置。给定一个新的图像，Situate使用这些模型试图通过主动搜索程序（即创建一个定位框）定位图像中情境的每个预期成分。状态使用所得到的基础来计算指示新图像被判断为包含情况的实例的程度的分数。这样的分数可以用来将图像集中在一个检索系统中。在这里所描述的初步研究中，我们通过比较斯台特与两个基线方法的性能以及基于“场景图”的相关语义图像检索系统来证明这个系统的前景。

##### URL
[https://arxiv.org/abs/1711.00088](https://arxiv.org/abs/1711.00088)

##### PDF
[https://arxiv.org/pdf/1711.00088](https://arxiv.org/pdf/1711.00088)

