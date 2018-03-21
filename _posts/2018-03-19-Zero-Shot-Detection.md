---
layout: post
title: "Zero-Shot Detection"
date: 2018-03-19 18:48:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Pengkai Zhu, Hanxiao Wang, Tolga Bolukbasi, Venkatesh Saligrama
mathjax: true
---

* content
{:toc}

##### Abstract
As we move towards large-scale object detection, it is unrealistic to expect annotated training data for all object classes at sufficient scale, and so methods capable of unseen object detection are required. We propose a novel zero-shot method based on training an end-to-end model that fuses semantic attribute prediction with visual features to propose object bounding boxes for seen and unseen classes. While we utilize semantic features during training, our method is agnostic to semantic information for unseen classes at test-time. Our method retains the efficiency and effectiveness of YOLO for objects seen during training, while improving its performance for novel and unseen objects. The ability of state-of-art detection methods to learn discriminative object features to reject background proposals also limits their performance for unseen objects. 
 We posit that, to detect unseen objects, we must incorporate semantic information into the visual domain so that the learned visual features reflect this information and leads to improved recall rates for unseen objects. We test our method on PASCAL VOC and MS COCO dataset and observed significant improvements on the average precision of unseen classes.

##### Abstract (translated by Google)
随着我们朝着大规模目标检测迈进，期望足够大的所有目标类别的注释训练数据是不切实际的，因此需要能够进行看不见的目标检测的方法。我们提出了一种基于训练端点到端模型的新颖的零炮法，该模型将语义属性预测与视觉特征相融合，以提供可见和不可见类的对象边界框。虽然我们在训练期间利用语义特征，但我们的方法在测试时间对于看不见的类的语义信息是不可知的。我们的方法保留了YOLO在培训期间看到的物体的效率和有效性，同时改善了其对于新颖和不可见物体的性能。最先进的检测方法学习区分对象特征以拒绝背景建议的能力也限制了它们对于看不见的对象的性能。
 我们假设，为了检测看不见的对象，我们必须将语义信息纳入视觉领域，以便学习的视觉特征能够反映这些信息，从而提高未见物体的召回率。我们在PASCAL VOC和MS COCO数据集上测试了我们的方法，并观察到看不见的类的平均精度的显着提高。

##### URL
[http://arxiv.org/abs/1803.07113](http://arxiv.org/abs/1803.07113)

##### PDF
[http://arxiv.org/pdf/1803.07113](http://arxiv.org/pdf/1803.07113)

