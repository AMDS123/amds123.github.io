---
layout: post
title: "Learning Semantics for Image Annotation"
date: 2017-05-15 07:45:10
categories: arXiv_CV
tags: arXiv_CV Image_Caption Relation
author: Amara Tariq, Hassan Foroosh
mathjax: true
---

* content
{:toc}

##### Abstract
Image search and retrieval engines rely heavily on textual annotation in order to match word queries to a set of candidate images. A system that can automatically annotate images with meaningful text can be highly beneficial for such engines. Currently, the approaches to develop such systems try to establish relationships between keywords and visual features of images. In this paper, We make three main contributions to this area: (i) We transform this problem from the low-level keyword space to the high-level semantics space that we refer to as the "{\em image theme}", (ii) Instead of treating each possible keyword independently, we use latent Dirichlet allocation to learn image themes from the associated texts in a training phase. Images are then annotated with image themes rather than keywords, using a modified continuous relevance model, which takes into account the spatial coherence and the visual continuity among images of common theme. (iii) To achieve more coherent annotations among images of common theme, we have integrated ConceptNet in learning the semantics of images, and hence augment image descriptions beyond annotations provided by humans. Images are thus further annotated by a few most significant words of the prominent image theme. Our extensive experiments show that a coherent theme-based image annotation using high-level semantics results in improved precision and recall as compared with equivalent classical keyword annotation systems.

##### Abstract (translated by Google)
图像搜索和检索引擎很大程度上依赖于文本注释，以便将单词查询匹配到一组候选图像。一个系统可以自动注释有意义的文字图像可以是非常有益的这种引擎。目前，开发这种系统的方法试图建立关键字与图像视觉特征之间的关系。在本文中，我们对这个领域做出了三个主要的贡献：（i）我们把这个问题从低级关键字空间转换到我们称之为“{\ em图像主题}”的高级语义空间， ii）我们不用独立处理每个可能的关键词，而是在训练阶段使用潜在的狄利克雷分配来从关联的文本中学习图像主题。然后用图像主题而不是关键字对图像进行注释，使用修改后的连续相关性模型，该模型考虑了共同主题图像之间的空间连贯性和视觉连续性。 （iii）为了在共同主题的图像中实现更加连贯的注释，我们已经将ConceptNet整合到学习图像的语义中，并且因此增加了图像描述而不是由人类提供的注释。图像因此被突出图像主题的几个最重要的单词进一步注释。我们广泛的实验表明，与等价的经典关键词注释系统相比，使用高级语义的基于主题的连贯图像注释导致提高的精度和查全率。

##### URL
[https://arxiv.org/abs/1705.05102](https://arxiv.org/abs/1705.05102)

##### PDF
[https://arxiv.org/pdf/1705.05102](https://arxiv.org/pdf/1705.05102)

