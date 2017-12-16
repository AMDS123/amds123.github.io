---
layout: post
title: "Region-Based Image Retrieval Revisited"
date: 2017-09-26 16:09:48
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Deep_Learning Relation Recommendation
author: Ryota Hinami, Yusuke Matsui, Shin'ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Region-based image retrieval (RBIR) technique is revisited. In early attempts at RBIR in the late 90s, researchers found many ways to specify region-based queries and spatial relationships; however, the way to characterize the regions, such as by using color histograms, were very poor at that time. Here, we revisit RBIR by incorporating semantic specification of objects and intuitive specification of spatial relationships. Our contributions are the following. First, to support multiple aspects of semantic object specification (category, instance, and attribute), we propose a multitask CNN feature that allows us to use deep learning technique and to jointly handle multi-aspect object specification. Second, to help users specify spatial relationships among objects in an intuitive way, we propose recommendation techniques of spatial relationships. In particular, by mining the search results, a system can recommend feasible spatial relationships among the objects. The system also can recommend likely spatial relationships by assigned object category names based on language prior. Moreover, object-level inverted indexing supports very fast shortlist generation, and re-ranking based on spatial constraints provides users with instant RBIR experiences.

##### Abstract (translated by Google)
重新研究基于区域的图像检索（RBIR）技术。在90年代后期的早期RBIR尝试中，研究人员找到了很多方法来指定基于区域的查询和空间关系;然而，用颜色直方图来表征这些区域的方法在当时是非常差的。在这里，我们通过结合对象的语义规范和直观的空间关系规范来重新审视RBIR。我们的贡献如下。首先，为了支持语义对象规范（类别，实例和属性）的多个方面，我们提出了一个多任务CNN特性，允许我们使用深度学习技术并共同处理多方面对象规范。其次，为了帮助用户直观地指定对象之间的空间关系，我们提出了空间关系的推荐技术。具体而言，通过挖掘搜索结果，系统可以推荐对象之间的可行的空间关系。系统还可以根据先前的语言，通过指定的对象类别名称推荐可能的空间关系。此外，对象级倒排索引支持非常快速的候选名单生成，并且基于空间约束的重排可以为用户提供即时的RBIR体验。

##### URL
[https://arxiv.org/abs/1709.09106](https://arxiv.org/abs/1709.09106)

##### PDF
[https://arxiv.org/pdf/1709.09106](https://arxiv.org/pdf/1709.09106)

