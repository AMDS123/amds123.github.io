---
layout: post
title: "Semi-Supervised Multi-Organ Segmentation via Deep Multi-Planar Co-Training"
date: 2018-05-12 01:23:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention GAN Deep_Learning
author: Yuyin Zhou, Yan Wang, Peng Tang, Wei Shen, Elliot K. Fishman, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In multi-organ segmentation of abdominal CT scans, most existing fully supervised deep learning algorithms require lots of voxel-wise annotations, which are usually difficult, expensive, and slow to obtain. In comparison, massive unlabeled 3D CT volumes are usually easily accessible. Current mainstream works to address the semi-supervised biomedical image segmentation problem are mostly graph-based. By contrast, deep network based semi-supervised learning methods have not drawn much attention in this field. In this work, we propose Deep Multi-Planar Co-Training (DMPCT), whose contributions can be divided into two folds: 1) The deep model is learned in a co-training style which can mine consensus information from multiple planes like the sagittal, coronal, and axial planes; 2) Multi-planar fusion is applied to generate more reliable pseudo-labels, which alleviates the errors occurring in the pseudo-labels and thus can help to train better segmentation networks. Experiments are done on our newly collected large dataset with 100 unlabeled cases as well as 210 labeled cases where 16 anatomical structures are manually annotated by four radiologists and confirmed by a senior expert. The results suggest that DMPCT significantly outperforms the fully supervised method by more than 4% especially when only a small set of annotations is used.

##### Abstract (translated by Google)
在腹部CT扫描的多器官分割中，大多数现有的完全监督深度学习算法需要大量体素明智的注释，这通常困难，昂贵并且获得缓慢。相比之下，大量未标记的3D CT体积通常易于获取。目前主流的解决半监督生物医学图像分割问题的主要工作大多是基于图形的。相比之下，基于深度网络的半监督学习方法在这一领域并未引起足够的重视。在这项工作中，我们提出深度多平面共训练（DMPCT），其贡献可以分为两个层次：1）深层模型是以共同训练方式学习的，可以从多个平面挖掘共识信息，如矢状位，冠状面和轴面; 2）应用多平面融合生成更可靠的伪标签，从而减少伪标签中出现的错误，从而有助于训练更好的分割网络。在我们新近收集的大型数据集上进行实验，其中包含100个未标记病例以及210个标记病例，其中16个解剖结构由4名放射科医师手动注释并由资深专家确认。结果表明，DMPCT显着优于全监督方法超过4％，特别是当仅使用一小组注释时。

##### URL
[http://arxiv.org/abs/1804.02586](http://arxiv.org/abs/1804.02586)

##### PDF
[http://arxiv.org/pdf/1804.02586](http://arxiv.org/pdf/1804.02586)

