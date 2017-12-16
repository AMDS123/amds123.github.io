---
layout: post
title: "Object Classification with Joint Projection and Low-rank Dictionary Learning"
date: 2016-12-05 23:49:26
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Relation Recognition
author: Homa Foroughi, Nilanjan Ray, Hong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
For an object classification system, the most critical obstacles towards real-world applications are often caused by large intra-class variability, arising from different lightings, occlusion and corruption, in limited sample sets. Most methods in the literature would fail when the training samples are heavily occluded, corrupted or have significant illumination or viewpoint variations. Besides, most of the existing methods and especially deep learning-based methods, need large training sets to achieve a satisfactory recognition performance. Although using the pre-trained network on a generic large-scale dataset and fine-tune it to the small-sized target dataset is a widely used technique, this would not help when the content of base and target datasets are very different. To address these issues, we propose a joint projection and low-rank dictionary learning method using dual graph constraints (JP-LRDL). The proposed joint learning method would enable us to learn the features on top of which dictionaries can be better learned, from the data with large intra-class variability. Specifically, a structured class-specific dictionary is learned and the discrimination is further improved by imposing a graph constraint on the coding coefficients, that maximizes the intra-class compactness and inter-class separability. We also enforce low-rank and structural incoherence constraints on sub-dictionaries to make them more compact and robust to variations and outliers and reduce the redundancy among them, respectively. To preserve the intrinsic structure of data and penalize unfavourable relationship among training samples simultaneously, we introduce a projection graph into the framework, which significantly enhances the discriminative ability of the projection matrix and makes the method robust to small-sized and high-dimensional datasets.

##### Abstract (translated by Google)
对于一个对象分类系统来说，实际应用中最关键的障碍往往是由于在有限的样本集中由于不同的照明，遮挡和腐败而产生的较大的类内可变性引起的。当训练样本严重遮挡，损坏或具有明显的照明或视点变化时，文献中的大多数方法将失败。此外，现有的大多数方法，尤其是基于深度学习的方法，都需要大量的训练集才能获得满意的识别性能。尽管在通用的大规模数据集上使用预先训练的网络并将其微调到小尺寸的目标数据集是一种广泛使用的技术，但是当基本数据集和目标数据集的内容非常不同时，这将无济于事。为了解决这些问题，我们提出了一个使用双图约束（JP-LRDL）的联合投影和低秩字典学习方法。所提出的联合学习方法将使我们能够从具有较大类内变异性的数据中学习哪些字典可以更好地学习的特征。具体而言，通过对编码系数施加图形约束来学习结构化的类别特定的字典，并且使类内紧凑性和类间可分性最大化，从而进一步提高了区分度。我们还对子词典实施低秩和结构不连贯约束，使它们对变异和异常更加紧凑和强健，并分别减少它们之间的冗余。为了保持数据的内在结构，同时惩罚训练样本间的不利关系，在框架中引入投影图，大大提高了投影矩阵的判别能力，使得该方法对小尺寸，高维数据集具有鲁棒性。

##### URL
[https://arxiv.org/abs/1612.01594](https://arxiv.org/abs/1612.01594)

##### PDF
[https://arxiv.org/pdf/1612.01594](https://arxiv.org/pdf/1612.01594)

