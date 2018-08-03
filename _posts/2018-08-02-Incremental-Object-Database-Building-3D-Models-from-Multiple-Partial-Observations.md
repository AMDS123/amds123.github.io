---
layout: post
title: "Incremental Object Database: Building 3D Models from Multiple Partial Observations"
date: 2018-08-02 11:19:55
categories: arXiv_RO
tags: arXiv_RO Knowledge Segmentation Face
author: Fadri Furrer, Tonci Novkovic, Marius Fehr, Abel Gawel, Margarita Grinvald, Torsten Sattler, Roland Siegwart, Juan Nieto
mathjax: true
---

* content
{:toc}

##### Abstract
Collecting 3D object datasets involves a large amount of manual work and is time consuming. Getting complete models of objects either requires a 3D scanner that covers all the surfaces of an object or one needs to rotate it to completely observe it. We present a system that incrementally builds a database of objects as a mobile agent traverses a scene. Our approach requires no prior knowledge of the shapes present in the scene. Object-like segments are extracted from a global segmentation map, which is built online using the input of segmented RGB-D images. These segments are stored in a database, matched among each other, and merged with other previously observed instances. This allows us to create and improve object models on the fly and to use these merged models to reconstruct also unobserved parts of the scene. The database contains each (potentially merged) object model only once, together with a set of poses where it was observed. We evaluate our pipeline with one public dataset, and on a newly created Google Tango dataset containing four indoor scenes with some of the objects appearing multiple times, both within and across scenes.

##### Abstract (translated by Google)
收集3D对象数据集涉及大量的手动工作并且非常耗时。获得完整的物体模型要么需要3D扫描仪覆盖物体的所有表面，要么需要旋转它以完全观察物体。我们提出了一个系统，当移动代理遍历场景时，该系统逐步构建对象数据库。我们的方法不需要事先知道场景中存在的形状。从全局分割图提取类似对象的片段，该全局分割图使用分段的RGB-D图像的输入在线构建。这些段存储在数据库中，彼此匹配，并与其他先前观察到的实例合并。这允许我们即时创建和改进对象模型，并使用这些合并的模型来重建场景中未观察到的部分。数据库仅包含每个（可能合并的）对象模型，以及观察到的一组姿势。我们使用一个公共数据集评估我们的管道，并在新创建的Google Tango数据集中包含四个室内场景，其中一些对象在场景内和场景中多次出现。

##### URL
[http://arxiv.org/abs/1808.00760](http://arxiv.org/abs/1808.00760)

##### PDF
[http://arxiv.org/pdf/1808.00760](http://arxiv.org/pdf/1808.00760)

