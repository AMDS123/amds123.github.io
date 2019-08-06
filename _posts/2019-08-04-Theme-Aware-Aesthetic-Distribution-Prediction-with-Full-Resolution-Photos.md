---
layout: post
title: "Theme Aware Aesthetic Distribution Prediction with Full Resolution Photos"
date: 2019-08-04 10:03:38
categories: arXiv_CV
tags: arXiv_CV QA Prediction Relation
author: Gengyun Jia, Peipei Li, Ran He
mathjax: true
---

* content
{:toc}

##### Abstract
Aesthetic quality assessment (AQA) of photos is a challenging task due to the subjective and diverse factors in human assessment process. Nowadays, it is common to tackle AQA with deep neural networks (DNNs) for their superior performance on modeling such complex relations. However, traditional DNNs require fix-sized inputs, and resizing various inputs to a uniform size may significantly change their aesthetic features. Such transformations lead to the mismatches between photos and their aesthetic evaluations. Existing methods usually adopt two solutions for it. Some methods directly crop fix-sized patches from the inputs. The others alternately capture the aesthetic features from pre-defined multi-size inputs by inserting adaptive pooling or removing fully connected layers. However, the former destroys the global structures and layout information, which are crucial in most situations. The latter has to resize images into several pre-defined sizes, which is not enough to reflect the diversity of image sizes, and the aesthetic features are still destroyed. To address this issue, we propose a simple and effective method that can handle the arbitrary sizes of batch inputs to achieve AQA on the full resolution images by combining image padding with ROI (region of interest) pooling. Padding keeps inputs of the same size, while ROI pooling cuts off the forward propagation of features on padding regions, thus eliminates the side effects of padding. Besides, we observe that the same image may receive different scores under different themes, which we call the theme criterion bias. However, previous works only focus on the aesthetic features of the images and ignore the criterion bias brought by their themes. In this paper, we introduce the theme information and propose a theme aware model. Extensive experiments prove the effectiveness of the proposed method over the state-of-the-arts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01308](http://arxiv.org/abs/1908.01308)

##### PDF
[http://arxiv.org/pdf/1908.01308](http://arxiv.org/pdf/1908.01308)

