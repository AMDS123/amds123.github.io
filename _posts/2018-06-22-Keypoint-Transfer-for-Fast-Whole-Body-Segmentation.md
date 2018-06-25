---
layout: post
title: "Keypoint Transfer for Fast Whole-Body Segmentation"
date: 2018-06-22 15:18:10
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation GAN
author: Christian Wachinger, Matthew Toews, Georg Langs, William Wells, Polina Golland
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an approach for image segmentation based on sparse correspondences between keypoints in testing and training images. Keypoints represent automatically identified distinctive image locations, where each keypoint correspondence suggests a transformation between images. We use these correspondences to transfer label maps of entire organs from the training images to the test image. The keypoint transfer algorithm includes three steps: (i) keypoint matching, (ii) voting-based keypoint labeling, and (iii) keypoint-based probabilistic transfer of organ segmentations. We report segmentation results for abdominal organs in whole-body CT and MRI, as well as in contrast-enhanced CT and MRI. Our method offers a speed-up of about three orders of magnitude in comparison to common multi-atlas segmentation, while achieving an accuracy that compares favorably. Moreover, keypoint transfer does not require the registration to an atlas or a training phase. Finally, the method allows for the segmentation of scans with highly variable field-of-view.

##### Abstract (translated by Google)
我们引入了一种基于测试和训练图像中关键点之间稀疏对应关系的图像分割方法。关键点表示自动识别的独特图像位置，其中每个关键点对应表示图像之间的转换。我们使用这些对应关系将整个器官的标签图从训练图像转移到测试图像。关键点转移算法包括三个步骤：（i）关键点匹配，（ii）基于投票的关键点标记，以及（iii）基于关键点的器官分割的概率转移。我们报告全身CT和MRI腹部器官的分割结果，以及对比增强CT和MRI。我们的方法与普通的多图集分割相比，加快了约三个数量级的速度，同时实现了比较好的精确度。此外，关键转移不需要注册图册或培训阶段。最后，该方法允许用高度可变的视场对扫描进行分割。

##### URL
[http://arxiv.org/abs/1806.08723](http://arxiv.org/abs/1806.08723)

##### PDF
[http://arxiv.org/pdf/1806.08723](http://arxiv.org/pdf/1806.08723)

