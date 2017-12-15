---
layout: post
title: "CRAFT Objects from Images"
date: 2016-04-12 03:57:48
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Classification Detection
author: Bin Yang, Junjie Yan, Zhen Lei, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is a fundamental problem in image understanding. One popular solution is the R-CNN framework and its fast versions. They decompose the object detection problem into two cascaded easier tasks: 1) generating object proposals from images, 2) classifying proposals into various object categories. Despite that we are handling with two relatively easier tasks, they are not solved perfectly and there's still room for improvement. In this paper, we push the "divide and conquer" solution even further by dividing each task into two sub-tasks. We call the proposed method "CRAFT" (Cascade Region-proposal-network And FasT-rcnn), which tackles each task with a carefully designed network cascade. We show that the cascade structure helps in both tasks: in proposal generation, it provides more compact and better localized object proposals; in object classification, it reduces false positives (mainly between ambiguous categories) by capturing both inter- and intra-category variances. CRAFT achieves consistent and considerable improvement over the state-of-the-art on object detection benchmarks like PASCAL VOC 07/12 and ILSVRC.

##### Abstract (translated by Google)
目标检测是图像理解的一个基本问题。一个流行的解决方案是R-CNN框架及其快速版本。他们将对象检测问题分解为两个级联的简单任务：1）从图像生成对象提议，2）将提议分类为各种对象类别。尽管我们正在处理两个相对较简单的任务，但这些任务并没有完全解决，还有改进的空间。在本文中，我们更进一步推动“分而治之”的解决方案，把每个任务分成两个子任务。我们称之为“CRAFT”（Cascade Region-proposal-network和FasT-rcnn）的方法，该方法用精心设计的网络级联处理每个任务。我们证明级联结构有助于两个任务：在提案生成中，它提供更紧凑和更好的本地化对象提议;在对象分类中，通过捕获类内和类内差异来减少误报（主要在不明确的类别之间）。 CRAFT在像PASCAL VOC 07/12和ILSVRC这样的物体检测基准方面达到了一致的和可观的改进。

##### URL
[https://arxiv.org/abs/1604.03239](https://arxiv.org/abs/1604.03239)

##### PDF
[https://arxiv.org/pdf/1604.03239](https://arxiv.org/pdf/1604.03239)

