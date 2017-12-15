---
layout: post
title: "Detangling People: Individuating Multiple Close People and Their Body Parts via Region Assembly"
date: 2016-04-13 17:35:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Optimization Detection Relation Recognition
author: Hao Jiang, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
Today's person detection methods work best when people are in common upright poses and appear reasonably well spaced out in the image. However, in many real images, that's not what people do. People often appear quite close to each other, e.g., with limbs linked or heads touching, and their poses are often not pedestrian-like. We propose an approach to detangle people in multi-person images. We formulate the task as a region assembly problem. Starting from a large set of overlapping regions from body part semantic segmentation and generic object proposals, our optimization approach reassembles those pieces together into multiple person instances. It enforces that the composed body part regions of each person instance obey constraints on relative sizes, mutual spatial relationships, foreground coverage, and exclusive label assignments when overlapping. Since optimal region assembly is a challenging combinatorial problem, we present a Lagrangian relaxation method to accelerate the lower bound estimation, thereby enabling a fast branch and bound solution for the global optimum. As output, our method produces a pixel-level map indicating both 1) the body part labels (arm, leg, torso, and head), and 2) which parts belong to which individual person. Our results on three challenging datasets show our method is robust to clutter, occlusion, and complex poses. It outperforms a variety of competing methods, including existing detector CRF methods and region CNN approaches. In addition, we demonstrate its impact on a proxemics recognition task, which demands a precise representation of "whose body part is where" in crowded images.

##### Abstract (translated by Google)
当人们处于共同的直立姿势，并且在图像中显得相当合理时，今天的人物检测方法效果最好。但是，在许多真实的图像中，这不是人们所做的。人们往往看起来相当接近，例如四肢相连或头部相碰，而且姿势往往不像行人那样。我们提出一种方法来解决多人图像中的人。我们把这个任务制定成一个地区集会问题。从身体部分语义分割和通用对象建议的大量重叠区域开始，我们的优化方法将这些部分重新组合成多个人物实例。它强制每个人实例的组成身体部位区域遵守相对大小，相互空间关系，前景覆盖范围和重叠时的专有标签分配的约束。由于最优区域组装是一个具有挑战性的组合问题，我们提出了拉格朗日松弛方法来加速下界估计，从而为全局最优化提供了一个快速的分支定界解决方案。作为输出，我们的方法产生一个像素级别的地图，指示1）身体部位标签（手臂，腿，躯干和头部），以及2）哪些部分属于哪个人。我们在三个具有挑战性的数据集上的结果表明，我们的方法对杂波，遮挡和复杂姿态是鲁棒的。它优于各种竞争方法，包括现有的探测器CRF方法和区域CNN方法。此外，我们还展示了它对临近认知任务的影响，这个任务要求在拥挤的图像中精确地表示“身体部位在哪里”。

##### URL
[https://arxiv.org/abs/1604.03880](https://arxiv.org/abs/1604.03880)

##### PDF
[https://arxiv.org/pdf/1604.03880](https://arxiv.org/pdf/1604.03880)

