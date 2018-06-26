---
layout: post
title: "Fast ASR-free and almost zero-resource keyword spotting using DTW and CNNs for humanitarian monitoring"
date: 2018-06-25 10:41:29
categories: arXiv_CL
tags: arXiv_CL CNN
author: Raghav Menon, Herman Kamper, John Quinn, Thomas Niesler
mathjax: true
---

* content
{:toc}

##### Abstract
We use dynamic time warping (DTW) as supervision for training a convolutional neural network (CNN) based keyword spotting system using a small set of spoken isolated keywords. The aim is to allow rapid deployment of a keyword spotting system in a new language to support urgent United Nations (UN) relief programmes in parts of Africa where languages are extremely under-resourced and the development of annotated speech resources is infeasible. First, we use 1920 recorded keywords (40 keyword types, 34 minutes of speech) as exemplars in a DTW-based template matching system and apply it to untranscribed broadcast speech. Then, we use the resulting DTW scores as targets to train a CNN on the same unlabelled speech. In this way we use just 34 minutes of labelled speech, but leverage a large amount of unlabelled data for training. While the resulting CNN keyword spotter cannot match the performance of the DTW-based system, it substantially outperforms a CNN classifier trained only on the keywords, improving the area under the ROC curve from 0.54 to 0.64. Because our CNN system is several orders of magnitude faster at runtime than the DTW system, it represents the most viable keyword spotter on this extremely limited dataset.

##### Abstract (translated by Google)
我们使用动态时间规整（DTW）作为监督来训练基于卷积神经网络（CNN）的关键词识别系统，使用一小组口头隔离关键字。其目的是以一种新语言快速部署关键词定位系统，以支持非洲部分地区的紧急联合国（UN）救援计划，这些地区的语言资源极度不足，并且注释语音资源的开发不可行。首先，我们在基于DTW的模板匹配系统中使用1920个记录的关键词（40个关键字类型，34分钟的语音）作为示例，并将其应用于未转录的广播语音。然后，我们使用得到的DTW分数作为目标，在相同的未标记语音上训练CNN。通过这种方式，我们只用了34分钟的带标签的演讲，但却利用了大量未标记的数据进行培训。虽然由此产生的CNN关键词spotter无法与基于DTW的系统的性能相匹配，但它大大优于仅在关键字上训练的CNN分类器，从而将ROC曲线下的面积从0.54改进为0.64。由于我们的CNN系统在运行时比DTW系统快几个数量级，因此它代表了这个极其有限的数据集上最可行的关键字侦测器。

##### URL
[http://arxiv.org/abs/1806.09374](http://arxiv.org/abs/1806.09374)

##### PDF
[http://arxiv.org/pdf/1806.09374](http://arxiv.org/pdf/1806.09374)

