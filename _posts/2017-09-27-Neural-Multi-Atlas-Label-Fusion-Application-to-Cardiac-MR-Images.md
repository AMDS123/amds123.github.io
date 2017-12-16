---
layout: post
title: "Neural Multi-Atlas Label Fusion: Application to Cardiac MR Images"
date: 2017-09-27 17:25:17
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Heran Yang, Jian Sun, Huibin Li, Lisheng Wang, Zongben Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-atlas segmentation approach is one of the most widely-used image segmentation techniques in biomedical applications. There are two major challenges in this category of methods, i.e., atlas selection and label fusion. In this paper, we propose a novel multi-atlas segmentation method that formulates multi-atlas segmentation in a deep learning framework for better solving these challenges. The proposed method, dubbed deep fusion net (DFN), is a deep architecture that integrates a feature extraction subnet and a non-local patch-based label fusion (NL-PLF) subnet in a single network. The network parameters are learned by end-to-end training strategy for automatically learning deep features that enable optimal performance in a NL-PLF framework. Besides, the learned deep features are further utilized in defining a similarity measure for atlas selection. We evaluate our proposed method on two public cardiac MR databases of SATA-13 and LV-09 for left ventricle segmentation, and our learned DFNs with extracted deep features for atlas selection at testing phase achieve state-of-the-art accuracies, e.g., 0.833 in averaged Dice metric (ADM) on SATA-13 database and 0.95 in ADM for epicardium segmentation on LV-09 database. Besides, our method is robust to the cross-database evaluation, e.g., the DFN learned on LV-09 database achieves 0.815 in ADM on SATA-13 database. We also test our proposed method on Cardiac Atlas Project (CAP) testing set of MICCAI 2013 SATA Segmentation Challenge, and our method achieves 0.815 in Dice metric, ranking as the highest result on this dataset.

##### Abstract (translated by Google)
多图谱分割方法是生物医学应用中使用最广泛的图像分割技术之一。这类方法有两大挑战，即地图集选择和标签融合。在本文中，我们提出了一个新的多图集分割方法，在深度学习框架中制定多图集分割，以更好地解决这些挑战。该方法被称为深度融合网（DFN），是将特征提取子网和非局部基于块的标签融合（NL-PLF）子网在一个网络中集成的深层架构。通过端到端的培训策略学习网络参数，以自动学习在NL-PLF框架中实现最佳性能的深度特性。此外，学习深度特征进一步用于定义地图集选择的相似性度量。我们评估了我们提出的用于左心室分割的SATA-13和LV-09的两个公共心脏MR数据库的方法，并且我们学习的DFN在测试阶段提取了用于图谱选择的深度特征，实现了最新的精确度，在SATA-13数据库上的平均Dice度量（ADM）为0.833，在LV-09数据库中为0.95，心外膜分段为ADM。此外，我们的方法对于跨数据库评估是有效的，例如，在SATA-13数据库上，在LV-09数据库上学习的DFN在ADM上达到0.815。我们还测试了我们提出的在MICCAI 2013 SATA Segmentation Challenge的Cardiac Atlas Project（CAP）测试集上的方法，我们的方法在Dice指标中达到了0.815，在该数据集中排名最高。

##### URL
[https://arxiv.org/abs/1709.09641](https://arxiv.org/abs/1709.09641)

##### PDF
[https://arxiv.org/pdf/1709.09641](https://arxiv.org/pdf/1709.09641)

