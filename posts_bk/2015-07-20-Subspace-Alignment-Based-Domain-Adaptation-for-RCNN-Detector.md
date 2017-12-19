---
layout: post
title: "Subspace Alignment Based Domain Adaptation for RCNN Detector"
date: 2015-07-20 18:23:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Anant Raj, Vinay P. Namboodiri, Tinne Tuytelaars
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose subspace alignment based domain adaptation of the state of the art RCNN based object detector. The aim is to be able to achieve high quality object detection in novel, real world target scenarios without requiring labels from the target domain. While, unsupervised domain adaptation has been studied in the case of object classification, for object detection it has been relatively unexplored. In subspace based domain adaptation for objects, we need access to source and target subspaces for the bounding box features. The absence of supervision (labels and bounding boxes are absent) makes the task challenging. In this paper, we show that we can still adapt sub- spaces that are localized to the object by obtaining detections from the RCNN detector trained on source and applied on target. Then we form localized subspaces from the detections and show that subspace alignment based adaptation between these subspaces yields improved object detection. This evaluation is done by considering challenging real world datasets of PASCAL VOC as source and validation set of Microsoft COCO dataset as target for various categories.

##### Abstract (translated by Google)
在本文中，我们提出了基于子空间对齐的领域适应的最先进的基于RCNN的对象检测器。目标是能够在新颖的真实世界的目标场景中实现高质量的对象检测，而不需要来自目标域的标签。而在目标分类的情况下，已经研究了无监督的域适应，但是对于目标检测来说，它是相对尚未探索的。在对象的基于子空间的域适配中，我们需要访问边界框特征的源和目标子空间。缺乏监督（标签和边界框不存在）使任务具有挑战性。在本文中，我们表明，我们仍然可以通过从在源上训练的RCNN检测器获得检测并应用在目标上来调整本地化到对象的子空间。然后我们从检测中形成局部子空间，并且显示这些子空间之间的基于子空间对齐的适应产生改进的对象检测。通过考虑具有挑战性的PASCAL VOC现实世界数据集作为Microsoft COCO数据集的源和验证集作为各种类别的目标来完成此评估。

##### URL
[https://arxiv.org/abs/1507.05578](https://arxiv.org/abs/1507.05578)

##### PDF
[https://arxiv.org/pdf/1507.05578](https://arxiv.org/pdf/1507.05578)

