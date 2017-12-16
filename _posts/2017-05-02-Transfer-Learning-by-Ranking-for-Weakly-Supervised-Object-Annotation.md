---
layout: post
title: "Transfer Learning by Ranking for Weakly Supervised Object Annotation"
date: 2017-05-02 09:23:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Transfer_Learning Detection
author: Zhiyuan Shi, Parthipan Siva, Tao Xiang
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing approaches to training object detectors rely on fully supervised learning, which requires the tedious manual annotation of object location in a training set. Recently there has been an increasing interest in developing weakly supervised approach to detector training where the object location is not manually annotated but automatically determined based on binary (weak) labels indicating if a training image contains the object. This is a challenging problem because each image can contain many candidate object locations which partially overlaps the object of interest. Existing approaches focus on how to best utilise the binary labels for object location annotation. In this paper we propose to solve this problem from a very different perspective by casting it as a transfer learning problem. Specifically, we formulate a novel transfer learning based on learning to rank, which effectively transfers a model for automatic annotation of object location from an auxiliary dataset to a target dataset with completely unrelated object categories. We show that our approach outperforms existing state-of-the-art weakly supervised approach to annotating objects in the challenging VOC dataset.

##### Abstract (translated by Google)
大多数现有的训练物体检测器的方法依赖于完全监督学习，这需要在训练集中手动标注对象位置。近来，人们越来越有兴趣开发弱监督的探测器训练方法，其中对象位置不是手动注释的，而是基于指示训练图像是否包含对象的二进制（弱）标签自动确定。这是一个具有挑战性的问题，因为每个图像可以包含许多与感兴趣的对象部分重叠的候选对象位置。现有的方法着重于如何最好地利用二进制标签来进行对象位置注释。在本文中，我们提出从一个非常不同的角度解决这个问题，把它作为一个转移学习问题。具体而言，我们制定了一个基于学习排序的新型转移学习，有效地将一个从辅助数据集到对象类别完全不相关的目标数据集的自动标注对象位置的模型转换。我们表明，我们的方法胜过现有的最先进的弱监督方法，在具有挑战性的VOC数据集中注释对象。

##### URL
[https://arxiv.org/abs/1705.00873](https://arxiv.org/abs/1705.00873)

##### PDF
[https://arxiv.org/pdf/1705.00873](https://arxiv.org/pdf/1705.00873)

