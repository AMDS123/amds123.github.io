---
layout: post
title: "Query-Adaptive R-CNN for Open-Vocabulary Object Detection and Retrieval"
date: 2017-11-27 02:25:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Ryota Hinami, Shin'ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of open-vocabulary object retrieval and localization, which is to retrieve and localize objects from a very large-scale image database immediately by a textual query (e.g., a word or phrase). We first propose Query-Adaptive R-CNN, a simple yet strong framework for open-vocabulary object detection. Query-Adaptive R-CNN is a simple extension of Faster R-CNN from closed-vocabulary to open-vocabulary object detection: instead of learning a class-specific classifier and regressor, we learn a detector generator that transforms a text into classifier and regressor weights. All of its components can be learned in an end-to-end manner. Even with its simple architecture, it outperforms all state-of-the-art methods in the Flickr30k Entities phrase localization task. In addition, we propose negative phrase augmentation, a generic approach for exploiting hard negatives in the training of open-vocabulary object detection that significantly improves the discriminative ability of the generated classifier. We show that our system can retrieve and localize objects specified by a textual query from one million images in only 0.5 seconds.

##### Abstract (translated by Google)
我们解决开放词汇对象检索和定位的问题，即通过文本查询（例如，单词或短语）立即从超大规模图像数据库中检索和定位对象。我们首先提出了查询自适应R-CNN，一个简单而强大的开放词汇表对象检测框架。查询自适应R-CNN是从封闭词汇到开放词汇对象检测的更快R-CNN的简单扩展：我们不是学习一个特定类别的分类器和回归器，而是学习一个将文本转换为分类器和回归器的检测器生成器权重。所有的组件都可以以端到端的方式学习。即使采用了简单的架构，它也比Flickr30k Entities短语本地化任务中的所有最先进的方法都要好。另外，我们提出否定词组增强（negative phrase augmentation），这是一种利用开放词汇对象检测的训练中的硬性否定的通用方法，其显着地提高了生成的分类器的判别能力。我们显示我们的系统可以在0.5秒内从一百万张图像中检索和本地化由文本查询指定的对象。

##### URL
[https://arxiv.org/abs/1711.09509](https://arxiv.org/abs/1711.09509)

##### PDF
[https://arxiv.org/pdf/1711.09509](https://arxiv.org/pdf/1711.09509)

