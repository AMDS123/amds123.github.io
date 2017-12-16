---
layout: post
title: "Weakly Supervised Image Annotation and Segmentation with Objects and Attributes"
date: 2017-08-08 12:19:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised Semantic_Segmentation Prediction Detection Relation
author: Zhiyuan Shi, Yongxin Yang, Timothy M. Hospedales, Tao Xiang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to model complex visual scenes using a non-parametric Bayesian model learned from weakly labelled images abundant on media sharing sites such as Flickr. Given weak image-level annotations of objects and attributes without locations or associations between them, our model aims to learn the appearance of object and attribute classes as well as their association on each object instance. Once learned, given an image, our model can be deployed to tackle a number of vision problems in a joint and coherent manner, including recognising objects in the scene (automatic object annotation), describing objects using their attributes (attribute prediction and association), and localising and delineating the objects (object detection and semantic segmentation). This is achieved by developing a novel Weakly Supervised Markov Random Field Stacked Indian Buffet Process (WS-MRF-SIBP) that models objects and attributes as latent factors and explicitly captures their correlations within and across superpixels. Extensive experiments on benchmark datasets demonstrate that our weakly supervised model significantly outperforms weakly supervised alternatives and is often comparable with existing strongly supervised models on a variety of tasks including semantic segmentation, automatic image annotation and retrieval based on object-attribute associations.

##### Abstract (translated by Google)
我们建议使用非参数贝叶斯模型来模拟复杂的视觉场景，这些模型从媒体共享网站上丰富的弱标记图像（例如Flickr）学习而来。给定对象和属性的图像级注释较弱，而没有它们之间的位置或关联，我们的模型旨在学习对象和属性类的外观以及它们在每个对象实例上的关联。一旦学习完毕，给定一个图像，我们的模型可以被部署来以一种联合一致的方式处理一些视觉问题，包括识别场景中的对象（自动对象注释），使用它们的属性（属性预测和关联）来描述对象，并定位和划分对象（对象检测和语义分割）。这是通过开发一种新颖的弱监督马尔可夫随机场叠加印度自助过程（WS-MRF-SIBP）来实现的，该过程将物体和属性建模为潜在因素，并明确捕获超级像素内和跨超级像素的相关性。基准数据集上的大量实验表明，我们的弱监督模型明显优于弱监督的替代模型，并且经常与各种任务（包括语义分割，自动图像注释以及基于对象 - 属性关联的检索）上的现有强监督模型相比较。

##### URL
[https://arxiv.org/abs/1708.02459](https://arxiv.org/abs/1708.02459)

##### PDF
[https://arxiv.org/pdf/1708.02459](https://arxiv.org/pdf/1708.02459)

