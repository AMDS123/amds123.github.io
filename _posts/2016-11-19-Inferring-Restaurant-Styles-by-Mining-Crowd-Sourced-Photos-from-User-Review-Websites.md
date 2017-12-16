---
layout: post
title: "Inferring Restaurant Styles by Mining Crowd Sourced Photos from User-Review Websites"
date: 2016-11-19 04:27:28
categories: arXiv_CV
tags: arXiv_CV Review CNN Classification
author: Haofu Liao, Yucheng Li, Tianran Hu, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
When looking for a restaurant online, user uploaded photos often give people an immediate and tangible impression about a restaurant. Due to their informativeness, such user contributed photos are leveraged by restaurant review websites to provide their users an intuitive and effective search experience. In this paper, we present a novel approach to inferring restaurant types or styles (ambiance, dish styles, suitability for different occasions) from user uploaded photos on user-review websites. To that end, we first collect a novel restaurant photo dataset associating the user contributed photos with the restaurant styles from TripAdvior. We then propose a deep multi-instance multi-label learning (MIML) framework to deal with the unique problem setting of the restaurant style classification task. We employ a two-step bootstrap strategy to train a multi-label convolutional neural network (CNN). The multi-label CNN is then used to compute the confidence scores of restaurant styles for all the images associated with a restaurant. The computed confidence scores are further used to train a final binary classifier for each restaurant style tag. Upon training, the styles of a restaurant can be profiled by analyzing restaurant photos with the trained multi-label CNN and SVM models. Experimental evaluation has demonstrated that our crowd sourcing-based approach can effectively infer the restaurant style when there are a sufficient number of user uploaded photos for a given restaurant.

##### Abstract (translated by Google)
在网上寻找餐厅时，用户上传的照片往往给人们一个餐厅的直接和切实的印象。由于信息丰富，餐厅评论网站利用这些用户贡献的照片为用户提供直观而有效的搜索体验。在本文中，我们提出了一种新的方法来推断用户上传的照片在用户审查网站上的餐厅类型或风格（氛围，菜式，适合不同场合）。为此，我们首先收集一个新的餐厅照片数据集，将用户贡献的照片与TripAdvior的餐厅风格相关联。然后提出了深度多实例多标签学习（MIML）框架来处理餐厅风格分类任务的独特问题设置。我们采用两步引导策略来训练多标签卷积神经网络（CNN）。然后使用多标签CNN来计算与餐厅相关联的所有图像的餐厅风格的置信度分数。所计算的置信度分数还用于训练每个餐馆风格标签的最终二元分类器。经过培训，餐厅的风格可以通过分析餐厅的照片与训练有素的CNN和SVM模型进行分析。实验评估表明，基于群众采购的方法可以有效地推断餐厅的风格，当有足够数量的用户上传的照片为给定的餐厅。

##### URL
[https://arxiv.org/abs/1611.06301](https://arxiv.org/abs/1611.06301)

##### PDF
[https://arxiv.org/pdf/1611.06301](https://arxiv.org/pdf/1611.06301)

