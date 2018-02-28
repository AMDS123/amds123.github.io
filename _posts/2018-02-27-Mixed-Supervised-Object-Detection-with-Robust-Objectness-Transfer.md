---
layout: post
title: "Mixed Supervised Object Detection with Robust Objectness Transfer"
date: 2018-02-27 09:02:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Weakly_Supervised Detection
author: Yan Li, Junge Zhang, Jianguo Zhang, Kaiqi Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of leveraging existing fully labeled categories to improve the weakly supervised detection (WSD) of new object categories, which we refer to as mixed supervised detection (MSD). Different from previous MSD methods that directly transfer the pre-trained object detectors from existing categories to new categories, we propose a more reasonable and robust objectness transfer approach for MSD. In our framework, we first learn domain-invariant objectness knowledge from the existing fully labeled categories. The knowledge is modeled based on invariant features that are robust to the distribution discrepancy between the existing categories and new categories; therefore the resulting knowledge would generalize well to new categories and could assist detection models to reject distractors (e.g., object parts) in weakly labeled images of new categories. Under the guidance of learned objectness knowledge, we utilize multiple instance learning (MIL) to model the concepts of both objects and distractors and to further improve the ability of rejecting distractors in weakly labeled images. Our robust objectness transfer approach outperforms the existing MSD methods, and achieves state-of-the-art results on the challenging ILSVRC2013 detection dataset and the PASCAL VOC datasets.

##### Abstract (translated by Google)
在本文中，我们考虑利用现有的完全标记的类别来改进新的对象类别的弱监督检测（WSD），我们称之为混合监督检测（MSD）。与以前的MSD方法不同，该方法直接将预先训练的物体检测器从现有类别转移到新的类别，我们提出了一种更合理，更稳健的MSD物体转移方法。在我们的框架中，我们首先从现有完全标记的类别中学习领域不变对象知识。知识是基于对现有类别和新类别之间的分配差异具有鲁棒性的不变特征建模的;因此得到的知识将很好地归纳到新类别中，并且可以辅助检测模型在新类别的弱标记图像中拒绝分心者（例如，对象部分）。在学习对象知识的指导下，我们利用多重实例学习（MIL）来模拟对象和干扰对象的概念，并进一步提高在弱标记图像中拒绝干扰对象的能力。我们强大的对象传输方法优于现有的MSD方法，并在具有挑战性的ILSVRC2013检测数据集和PASCAL VOC数据集上实现了最先进的结果。

##### URL
[https://arxiv.org/abs/1802.09778](https://arxiv.org/abs/1802.09778)

##### PDF
[https://arxiv.org/pdf/1802.09778](https://arxiv.org/pdf/1802.09778)

