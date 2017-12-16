---
layout: post
title: "Cell Tracking via Proposal Generation and Selection"
date: 2017-05-09 15:30:39
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Deep_Learning Detection
author: Saad Ullah Akram, Juho Kannala, Lauri Eklund, Janne Heikkilä
mathjax: true
---

* content
{:toc}

##### Abstract
Microscopy imaging plays a vital role in understanding many biological processes in development and disease. The recent advances in automation of microscopes and development of methods and markers for live cell imaging has led to rapid growth in the amount of image data being captured. To efficiently and reliably extract useful insights from these captured sequences, automated cell tracking is essential. This is a challenging problem due to large variation in the appearance and shapes of cells depending on many factors including imaging methodology, biological characteristics of cells, cell matrix composition, labeling methodology, etc. Often cell tracking methods require a sequence-specific segmentation method and manual tuning of many tracking parameters, which limits their applicability to sequences other than those they are designed for. In this paper, we propose 1) a deep learning based cell proposal method, which proposes candidates for cells along with their scores, and 2) a cell tracking method, which links proposals in adjacent frames in a graphical model using edges representing different cellular events and poses joint cell detection and tracking as the selection of a subset of cell and edge proposals. Our method is completely automated and given enough training data can be applied to a wide variety of microscopy sequences. We evaluate our method on multiple fluorescence and phase contrast microscopy sequences containing cells of various shapes and appearances from ISBI cell tracking challenge, and show that our method outperforms existing cell tracking methods. Code is available at: this https URL

##### Abstract (translated by Google)
显微成像在理解发育和疾病中的许多生物过程中起着至关重要的作用。显微镜自动化的最新进展以及活细胞成像的方法和标记的发展导致捕获的图像数据量的快速增长。为了有效和可靠地从这些捕获的序列中提取有用的见解，自动化细胞跟踪是至关重这是一个具有挑战性的问题，因为细胞的外观和形状的巨大变化取决于许多因素，包括成像方法学，细胞的生物学特性，细胞基质成分，标记方法学等等。通常细胞追踪方法需要序列特异性分割方法，手动调整许多跟踪参数，这限制了它们适用于除了它们设计的序列之外的其他序列。在本文中，我们提出1）一种基于深度学习的细胞提议方法，其提出细胞的候选者及其得分，以及2）细胞追踪方法，其使用代表不同细胞事件的边缘并提出联合小区检测和跟踪作为小区和边缘提议的子集的选择。我们的方法是完全自动化的，并给予足够的训练数据可以应用于各种显微镜序列。我们评估我们的方法在多个荧光和相差显微镜序列包含各种形状和外观细胞从ISBI细胞跟踪挑战，并表明我们的方法胜过现有的细胞跟踪方法。代码位于：https网址

##### URL
[https://arxiv.org/abs/1705.03386](https://arxiv.org/abs/1705.03386)

##### PDF
[https://arxiv.org/pdf/1705.03386](https://arxiv.org/pdf/1705.03386)

