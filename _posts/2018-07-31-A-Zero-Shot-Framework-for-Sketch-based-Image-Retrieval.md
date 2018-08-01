---
layout: post
title: "A Zero-Shot Framework for Sketch-based Image Retrieval"
date: 2018-07-31 09:42:16
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Sasi Kiran Yelamarthi, Shiva Krishna Reddy, Ashish Mishra, Anurag Mittal
mathjax: true
---

* content
{:toc}

##### Abstract
Sketch-based image retrieval (SBIR) is the task of retrieving images from a natural image database that correspond to a given hand-drawn sketch. Ideally, an SBIR model should learn to associate components in the sketch (say, feet, tail, etc.) with the corresponding components in the image having similar shape characteristics. However, current evaluation methods simply focus only on coarse-grained evaluation where the focus is on retrieving images which belong to the same class as the sketch but not necessarily having the same shape characteristics as in the sketch. As a result, existing methods simply learn to associate sketches with classes seen during training and hence fail to generalize to unseen classes. In this paper, we propose a new benchmark for zero-shot SBIR where the model is evaluated in novel classes that are not seen during training. We show through extensive experiments that existing models for SBIR that are trained in a discriminative setting learn only class specific mappings and fail to generalize to the proposed zero-shot setting. To circumvent this, we propose a generative approach for the SBIR task by proposing deep conditional generative models that take the sketch as an input and fill the missing information stochastically. Experiments on this new benchmark created from the "Sketchy" dataset, which is a large-scale database of sketch-photo pairs demonstrate that the performance of these generative models is significantly better than several state-of-the-art approaches in the proposed zero-shot framework of the coarse-grained SBIR task.

##### Abstract (translated by Google)
基于草图的图像检索（SBIR）是从自然图像数据库中检索与给定的手绘草图相对应的图像的任务。理想情况下，SBIR模型应学会将草图中的组件（例如，脚，尾等）与具有相似形状特征的图像中的相应组件相关联。然而，当前的评估方法仅关注于粗粒度评估，其中焦点在于检索与草图属于同一类但不一定具有与草图中相同的形状特征的图像。因此，现有方法只是学习将草图与训练期间看到的类相关联，因此无法概括为看不见的类。在本文中，我们提出了零射击SBIR的新基准，其中模型在训练期间未见的新类别中进行评估。我们通过大量实验表明，在判别设置中训练的SBIR现有模型仅学习特定类别的映射，并且未能推广到建议的零点设置。为了避免这种情况，我们提出了一种生成SBIR任务的生成方法，提出了深度条件生成模型，该模型将草图作为输入并随机填充缺失的信息。从“Sketchy”数据集创建的这个新基准的实验，这是一个草图 - 照片对的大型数据库，表明这些生成模型的性能明显优于拟议零点中的几种最先进的方法。 - 粗粒度SBIR任务的框架。

##### URL
[http://arxiv.org/abs/1807.11724](http://arxiv.org/abs/1807.11724)

##### PDF
[http://arxiv.org/pdf/1807.11724](http://arxiv.org/pdf/1807.11724)

