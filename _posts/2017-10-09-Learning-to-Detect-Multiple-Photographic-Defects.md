---
layout: post
title: "Learning to Detect Multiple Photographic Defects"
date: 2017-10-09 20:15:48
categories: arXiv_CV
tags: arXiv_CV Summarization CNN Prediction Detection
author: Ning Yu, Xiaohui Shen, Zhe Lin, Radomir Mech, Connelly Barnes
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce the problem of simultaneously detecting multiple photographic defects. We aim at detecting the existence, severity, and potential locations of common photographic defects related to color, noise, blur and composition. The automatic detection of such defects could be used to provide users with suggestions for how to improve photos without the need to laboriously try various correction methods. Defect detection could also help users select photos of higher quality while filtering out those with severe defects in photo curation and summarization. To investigate this problem, we collected a large-scale dataset of user annotations on seven common photographic defects, which allows us to evaluate algorithms by measuring their consistency with human judgments. Our new dataset enables us to formulate the problem as a multi-task learning problem and train a multi-column deep convolutional neural network (CNN) to simultaneously predict the severity of all the defects. Unlike some existing single-defect estimation methods that rely on low-level statistics and may fail in many cases on natural photographs, our model is able to understand image contents and quality at a higher level. As a result, in our experiments, we show that our model has predictions with much higher consistency with human judgments than low-level methods as well as several baseline CNN models. Our model also performs better than an average human from our user study.

##### Abstract (translated by Google)
在本文中，我们介绍同时检测多个摄影缺陷的问题。我们的目标是检测与颜色，噪声，模糊和成分有关的常见照相缺陷的存在，严重程度和潜在位置。这些缺陷的自动检测可以用来向用户提供如何改善照片的建议，而不需要费力尝试各种校正方法。瑕疵检测还可以帮助用户选择更高质量的照片，同时筛选出照片处理和总结中存在严重缺陷的照片。为了研究这个问题，我们收集了七个常见摄影缺陷的用户注释的大规模数据集，这使我们可以通过测量它们与人类判断的一致性来评估算法。我们的新数据集使我们能够将问题表达为一个多任务学习问题，并训练一个多列深度卷积神经网络（CNN）来同时预测所有缺陷的严重程度。与一些依赖低级别统计的现有单缺陷估计方法不同，在许多情况下自然照片可能会失败，我们的模型能够更高层次地理解图像内容和质量。因此，在我们的实验中，我们表明，我们的模型预测与人类判断的一致性要比低水平的方法以及几个基线的CNN模型要高得多。我们的模型也比我们的用户研究中的普通人表现更好。

##### URL
[https://arxiv.org/abs/1612.01635](https://arxiv.org/abs/1612.01635)

##### PDF
[https://arxiv.org/pdf/1612.01635](https://arxiv.org/pdf/1612.01635)

