---
layout: post
title: "A Strategy of MR Brain Tissue Images' Suggestive Annotation Based on Modified U-Net"
date: 2018-07-19 16:02:41
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Yang Deng, Yao Sun, Yongpei Zhu, Mingwang Zhu, Kehong Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate segmentation of MR brain tissue is a crucial step for diagnosis,surgical planning, and treatment of brain abnormalities. However,it is a time-consuming task to be performed by medical experts. So, automatic and reliable segmentation methods are required. How to choose appropriate training dataset from limited labeled dataset rather than the whole also has great significance in saving training time. In addition, medical data labeled is too rare and expensive to obtain extensively, so choosing appropriate unlabeled dataset instead of all the datasets to annotate, which can attain at least same performance, is also very meaningful. To solve the problem above, we design an automatic segmentation method based on U-shaped deep convolutional network and obtain excellent result with average DSC metric of 0.8610, 0.9131, 0.9003 for Cerebrospinal Fluid (CSF), Gray Matter (GM) and White Matter (WM) respectively on the well-known IBSR18 dataset. We use bootstrapping algorithm for selecting the most effective training data and get more state-of-the-art segmentation performance by using only 50% of training data. Moreover, we propose a strategy of MR brain tissue images' suggestive annotation for unlabeled medical data based on the modified U-net. The proposed method performs fast and can be used in clinical.

##### Abstract (translated by Google)
MR脑组织的准确分割是诊断，手术计划和脑异常治疗的关键步骤。然而，由医学专家执行是一项耗时的任务。因此，需要自动且可靠的分割方法。如何从有限的标记数据集中选择合适的训练数据集而不是整体，对于节省训练时间也具有重要意义。此外，标记的医疗数据过于罕见且昂贵而无法广泛获得，因此选择适当的未标记数据集而不是所有数据集进行注释（这可以达到至少相同的性能）也是非常有意义的。为了解决上述问题，我们设计了一种基于U形深度卷积网络的自动分割方法，获得了优异的结果，平均DSC度量为0.8610,0.9131,0.9003，用于脑脊液（CSF），灰质（GM）和白质（ WM）分别对着名的IBSR18数据集。我们使用自举算法来选择最有效的训练数据，并通过仅使用50％的训练数据获得更多最先进的分割性能。此外，我们提出了一种基于改进U-net的MR脑组织图像对未标记医学数据的暗示性注释策略。该方法执行速度快，可用于临床。

##### URL
[https://arxiv.org/abs/1807.07510](https://arxiv.org/abs/1807.07510)

##### PDF
[https://arxiv.org/pdf/1807.07510](https://arxiv.org/pdf/1807.07510)

