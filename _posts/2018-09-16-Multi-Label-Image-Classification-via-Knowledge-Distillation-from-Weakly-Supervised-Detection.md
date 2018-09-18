---
layout: post
title: "Multi-Label Image Classification via Knowledge Distillation from Weakly-Supervised Detection"
date: 2018-09-16 14:35:03
categories: arXiv_AI
tags: arXiv_AI Knowledge Image_Classification Classification Prediction Detection
author: Yongcheng Liu, Lu Sheng, Jing Shao, Junjie Yan, Shiming Xiang, Chunhong Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-label image classification is a fundamental but challenging task towards general visual understanding. Existing methods found the region-level cues (e.g., features from RoIs) can facilitate multi-label classification. Nevertheless, such methods usually require laborious object-level annotations (i.e., object labels and bounding boxes) for effective learning of the object-level visual features. In this paper, we propose a novel and efficient deep framework to boost multi-label classification by distilling knowledge from weakly-supervised detection task without bounding box annotations. Specifically, given the image-level annotations, (1) we first develop a weakly-supervised detection (WSD) model, and then (2) construct an end-to-end multi-label image classification framework augmented by a knowledge distillation module that guides the classification model by the WSD model according to the class-level predictions for the whole image and the object-level visual features for object RoIs. The WSD model is the teacher model and the classification model is the student model. After this cross-task knowledge distillation, the performance of the classification model is significantly improved and the efficiency is maintained since the WSD model can be safely discarded in the test phase. Extensive experiments on two large-scale datasets (MS-COCO and NUS-WIDE) show that our framework achieves superior performances over the state-of-the-art methods on both performance and efficiency.

##### Abstract (translated by Google)
多标签图像分类是一般的视觉理解的基本但具有挑战性的任务。现有方法发现区域级别提示（例如，来自RoI的特征）可以促进多标签分类。然而，这些方法通常需要费力的对象级注释（即，对象标签和边界框）以有效地学习对象级视觉特征。在本文中，我们提出了一种新颖有效的深层框架，通过从弱监督检测任务中提取知识而不需要边界框注释来提升多标签分类。具体来说，给定图像级注释，（1）我们首先开发弱监督检测（WSD）模型，然后（2）构建一个端到端的多标签图像分类框架，由一个知识蒸馏模块增强根据整个图像的类级预测和对象RoI的对象级视觉特征，通过WSD模型指导分类模型。 WSD模型是教师模型，分类模型是学生模型。在这种跨任务知识蒸馏之后，分类模型的性能得到显着改善，并且由于可以在测试阶段安全地丢弃WSD模型，因此保持了效率。对两个大型数据集（MS-COCO和NUS-WIDE）进行的大量实验表明，我们的框架在性能和效率方面均优于最先进的方法。

##### URL
[http://arxiv.org/abs/1809.05884](http://arxiv.org/abs/1809.05884)

##### PDF
[http://arxiv.org/pdf/1809.05884](http://arxiv.org/pdf/1809.05884)

