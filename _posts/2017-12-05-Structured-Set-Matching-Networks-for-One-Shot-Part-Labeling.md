---
layout: post
title: "Structured Set Matching Networks for One-Shot Part Labeling"
date: 2017-12-05 19:03:08
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN
author: Jonghyun Choi, Jayant Krishnamurthy, Aniruddha Kembhavi, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
Diagrams often depict complex phenomena and serve as a good test bed for visual and textual reasoning. However, understanding diagrams using natural image understanding approaches requires large training datasets of diagrams, which are very hard to obtain. Instead, this can be addressed as a matching problem either between labeled diagrams, images or both. This problem is very challenging since the absence of significant color and texture renders local cues ambiguous and requires global reasoning. We consider the problem of one-shot part labeling: labeling multiple parts of an object in a target image given only a single source image of that category. For this set-to-set matching problem, we introduce the Structured Set Matching Network (SSMN), a structured prediction model that incorporates convolutional neural networks. The SSMN is trained using global normalization to maximize local match scores between corresponding elements and a global consistency score among all matched elements, while also enforcing a matching constraint between the two sets. The SSMN significantly outperforms several strong baselines on three label transfer scenarios: diagram-to-diagram, evaluated on a new diagram dataset of over 200 categories; image-to-image, evaluated on a dataset built on top of the Pascal Part Dataset; and image-to-diagram, evaluated on transferring labels across these datasets.

##### Abstract (translated by Google)
图表经常描绘复杂的现象，并作为视觉和文本推理的良好测试平台。然而，使用自然图像理解方法理解图需要大量难以获得的图的训练数据集。相反，这可以作为标记图，图像或两者之间的匹配问题来解决。这个问题是非常具有挑战性的，因为缺乏显着的颜色和纹理使得局部线索模糊不清并且需要全局推理。我们考虑一次性部分标签的问题：只给定目标图像中的对象的多个部分，只给出该类别的单个源图像。对于这个集合匹配问题，我们引入了结构化集合匹配网络（SSMN），一种结合了卷积神经网络的结构化预测模型。使用全局标准化对SSMN进行训练，以最大化相应元素之间的局部匹配得分和所有匹配元素之间的全局一致性得分，同时还强制两个集合之间的匹配约束。在三个标签传输方案中，SSMN显着优于几个强大的基线：图表到图表，在超过200个类别的新图表数据集上进行评估;图像到图像，评估建立在帕斯卡部件数据集之上的数据集;和图像到图表，在这些数据集上传输标签进行评估。

##### URL
[http://arxiv.org/abs/1712.01867](http://arxiv.org/abs/1712.01867)

##### PDF
[http://arxiv.org/pdf/1712.01867](http://arxiv.org/pdf/1712.01867)

