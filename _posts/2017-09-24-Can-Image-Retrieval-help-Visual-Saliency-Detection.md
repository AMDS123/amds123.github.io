---
layout: post
title: "Can Image Retrieval help Visual Saliency Detection?"
date: 2017-09-24 09:50:48
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Salient Optimization Detection
author: Shuang Li, Peter Mathews
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel image retrieval framework for visual saliency detection using information about salient objects contained within bounding box annotations for similar images. For each test image, we train a customized SVM from similar example images to predict the saliency values of its object proposals and generate an external saliency map (ES) by aggregating the regional scores. To overcome limitations caused by the size of the training dataset, we also propose an internal optimization module which computes an internal saliency map (IS) by measuring the low-level contrast information of the test image. The two maps, ES and IS, have complementary properties so we take a weighted combination to further improve the detection performance. Experimental results on several challenging datasets demonstrate that the proposed algorithm performs favorably against the state-of-the-art methods.

##### Abstract (translated by Google)
我们提出了一个新颖的图像检索框架的视觉显着性检测使用包含在相似图像的边界框注释中的显着对象的信息。对于每个测试图像，我们从相似的示例图像训练定制的SVM，以预测其对象提议的显着性值，并通过聚合区域得分来生成外部显着图（ES）。为了克服训练数据集大小的限制，我们还提出了一个内部优化模块，它通过测量测试图像的低级别对比度信息来计算内部显着图（IS）。 ES和IS这两个映射具有互补性，所以我们采用加权组合来进一步提高检测性能。在几个具有挑战性的数据集上的实验结果表明，所提出的算法对于最先进的方法有利。

##### URL
[https://arxiv.org/abs/1709.08172](https://arxiv.org/abs/1709.08172)

##### PDF
[https://arxiv.org/pdf/1709.08172](https://arxiv.org/pdf/1709.08172)

