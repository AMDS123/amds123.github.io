---
layout: post
title: "Multi-task human analysis in still images: 2D/3D pose, depth map, and multi-part segmentation"
date: 2019-05-08 10:55:02
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation Deep_Learning Relation
author: Daniel S&#xe1;nchez, Marc Oliu, Meysam Madadi, Xavier Bar&#xf3;, Sergio Escalera
mathjax: true
---

* content
{:toc}

##### Abstract
While many individual tasks in the domain of human analysis have recently received an accuracy boost from deep learning approaches, multi-task learning has mostly been ignored due to a lack of data. New synthetic datasets are being released, filling this gap with synthetic generated data. In this work, we analyze four related human analysis tasks in still images in a multi-task scenario by leveraging such datasets. Specifically, we study the correlation of 2D/3D pose estimation, body part segmentation and full-body depth estimation. These tasks are learned via the well-known Stacked Hourglass module such that each of the task-specific streams shares information with the others. The main goal is to analyze how training together these four related tasks can benefit each individual task for a better generalization. Results on the newly released SURREAL dataset show that all four tasks benefit from the multi-task approach, but with different combinations of tasks: while combining all four tasks improves 2D pose estimation the most, 2D pose improves neither 3D pose nor full-body depth estimation. On the other hand 2D parts segmentation can benefit from 2D pose but not from 3D pose. In all cases, as expected, the maximum improvement is achieved on those human body parts that show more variability in terms of spatial distribution, appearance and shape, e.g. wrists and ankles.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03003](http://arxiv.org/abs/1905.03003)

##### PDF
[http://arxiv.org/pdf/1905.03003](http://arxiv.org/pdf/1905.03003)

