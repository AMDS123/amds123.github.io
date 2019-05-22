---
layout: post
title: "TopoResNet: A hybrid deep learning architecture and its application to skin lesion classification"
date: 2019-05-13 21:16:39
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Deep_Learning
author: Yu-Min Chung, Chuan-Shen Hu, Austin Lawson, Clifford Smyth
mathjax: true
---

* content
{:toc}

##### Abstract
Skin cancer is one of the most common cancers in the United States. As technological advancements are made, algorithmic diagnosis of skin lesions is becoming more important. In this paper, we develop algorithms for segmenting the actual diseased area of skin in a given image of a skin lesion, and for classifying different types of skin lesions pictured in a given image. The cores of the algorithms used were based in persistent homology, an algebraic topology technique that is part of the rising field of Topological Data Analysis (TDA). The segmentation algorithm utilizes a similar concept to persistent homology that captures the robustness of segmented regions. For classification, we design two families of topological features from persistence diagrams---which we refer to as {\em persistence statistics} (PS) and {\em persistence curves} (PC), and use linear support vector machine as classifiers. We also combined those topological features, PS and PC, into ResNet-101 model, which we call {\em TopoResNet-101}, the results show that PS and PC are effective in two folds---improving classification performances and stabilizing the training process. Although convolutional features are the most important learning targets in CNN models, global information of images may be lost in the training process. Because topological features were extracted globally, our results show that the global property of topological features provide additional information to machine learning models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08607](http://arxiv.org/abs/1905.08607)

##### PDF
[http://arxiv.org/pdf/1905.08607](http://arxiv.org/pdf/1905.08607)

