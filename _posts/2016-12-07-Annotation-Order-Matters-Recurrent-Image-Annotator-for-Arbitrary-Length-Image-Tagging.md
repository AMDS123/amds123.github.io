---
layout: post
title: "Annotation Order Matters: Recurrent Image Annotator for Arbitrary Length Image Tagging"
date: 2016-12-07 19:57:02
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption
author: Jiren Jin, Hideki Nakayama
---

* content
{:toc}

##### Abstract
Automatic image annotation has been an important research topic in facilitating large scale image management and retrieval. Existing methods focus on learning image-tag correlation or correlation between tags to improve annotation accuracy. However, most of these methods evaluate their performance using top-k retrieval performance, where k is fixed. Although such setting gives convenience for comparing different methods, it is not the natural way that humans annotate images. The number of annotated tags should depend on image contents. Inspired by the recent progress in machine translation and image captioning, we propose a novel Recurrent Image Annotator (RIA) model that forms image annotation task as a sequence generation problem so that RIA can natively predict the proper length of tags according to image contents. We evaluate the proposed model on various image annotation datasets. In addition to comparing our model with existing methods using the conventional top-k evaluation measures, we also provide our model as a high quality baseline for the arbitrary length image tagging task. Moreover, the results of our experiments show that the order of tags in training phase has a great impact on the final annotation performance.

##### Abstract (translated by Google)
自动图像标注一直是促进大规模图像管理和检索的重要研究课题。现有方法专注于学习标签之间的相关性或标签之间的相关性，以提高注释的准确性。然而，这些方法中的大多数使用top-k检索性能评估其性能，其中k是固定的。尽管这样的设置为比较不同的方法提供了便利，但这不是人类对图像进行注释的自然方式。注释标签的数量应取决于图像内容。受机器翻译和图像字幕的最新进展的启发，我们提出了一种新的RIA（Recurrent Image Annotator）模型，将图像标注任务形成序列生成问题，使得RIA可以根据图像内容自然地预测标签的长度。我们评估提出的模型在各种图像注释数据集。除了将我们的模型与使用传统的top-k评估方法的现有方法进行比较外，我们还提供了我们的模型作为任意长度图像标记任务的高质量基线。此外，我们的实验结果表明，训练阶段的标签顺序对最终的注释性能有很大的影响。

##### URL
[https://arxiv.org/abs/1604.05225](https://arxiv.org/abs/1604.05225)

