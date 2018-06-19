---
layout: post
title: "Part-Aware Fine-grained Object Categorization using Weakly Supervised Part Detection Network"
date: 2018-06-16 07:08:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Classification Prediction Detection
author: Yabin Zhang, Kui Jia, Zhixin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained object categorization aims for distinguishing objects of subordinate categories that belong to the same entry-level object category. The task is challenging due to the facts that (1) training images with ground-truth labels are difficult to obtain, and (2) variations among different subordinate categories are subtle. It is well established that characterizing features of different subordinate categories are located on local parts of object instances. In fact, careful part annotations are available in many fine-grained categorization datasets. However, manually annotating object parts requires expertise, which is also difficult to generalize to new fine-grained categorization tasks. In this work, we propose a Weakly Supervised Part Detection Network (PartNet) that is able to detect discriminative local parts for use of fine-grained categorization. A vanilla PartNet builds on top of a base subnetwork two parallel streams of upper network layers, which respectively compute scores of classification probabilities (over subordinate categories) and detection probabilities (over a specified number of discriminative part detectors) for local regions of interest (RoIs). The image-level prediction is obtained by aggregating element-wise products of these region-level probabilities. To generate a diverse set of RoIs as inputs of PartNet, we propose a simple Discretized Part Proposals module (DPP) that directly targets for proposing candidates of discriminative local parts, with no bridging via object-level proposals. Experiments on the benchmark CUB-200-2011 and Oxford Flower 102 datasets show the efficacy of our proposed method for both discriminative part detection and fine-grained categorization. In particular, we achieve the new state-of-the-art performance on CUB-200-2011 dataset when ground-truth part annotations are not available.

##### Abstract (translated by Google)
细粒度对象分类旨在区分属于同一入门级对象类别的下属类别的对象。由于以下事实，该任务具有挑战性：（1）难以获得具有地面实况标签的图像，以及（2）不同下属类别之间的差异很微妙。已经确定，不同下属类别的特征特征位于对象实例的本地部分上。事实上，在许多细粒度的分类数据集中可以使用仔细的部分注释。然而，手动注释对象部分需要专业知识，这也很难推广到新的细粒度分类任务。在这项工作中，我们提出了一个弱监督部分检测网络（PartNet），它能够检测使用细粒度分类的区分性局部部分。一个vanilla PartNet基于一个基础子网络建立两个并行的上层网络层，它们分别计算局部感兴趣区域（RoIs）的分类概率（超过下属类别）和检测概率（超过指定数量的区分性部分检测器） ）。图像级预测是通过汇总这些区域级概率的元素明智的产品而获得的。为了产生一组不同的RoI作为PartNet的输入，我们提出了一个简单的Discretized Part Proposals模块（DPP），它直接针对提出区别性本地部分的候选人，并且没有通过对象级提案进行桥接。基准CUB-200-2011和Oxford Flower 102数据集上的实验显示了我们提出的用于区分性部分检测和细粒度分类的方法的功效。特别是，当地面实况部分注释不可用时，我们在CUB-200-2011数据集中实现了最新的最新性能。

##### URL
[http://arxiv.org/abs/1806.06198](http://arxiv.org/abs/1806.06198)

##### PDF
[http://arxiv.org/pdf/1806.06198](http://arxiv.org/pdf/1806.06198)

