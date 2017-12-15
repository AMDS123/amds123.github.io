---
layout: post
title: "Anatomy-Aware Measurement of Segmentation Accuracy"
date: 2016-04-16 01:49:22
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Hamid R. Tizhoosh, Ahmed A. Othman
mathjax: true
---

* content
{:toc}

##### Abstract
Quantifying the accuracy of segmentation and manual delineation of organs, tissue types and tumors in medical images is a necessary measurement that suffers from multiple problems. One major shortcoming of all accuracy measures is that they neglect the anatomical significance or relevance of different zones within a given segment. Hence, existing accuracy metrics measure the overlap of a given segment with a ground-truth without any anatomical discrimination inside the segment. For instance, if we understand the rectal wall or urethral sphincter as anatomical zones, then current accuracy measures ignore their significance when they are applied to assess the quality of the prostate gland segments. In this paper, we propose an anatomy-aware measurement scheme for segmentation accuracy of medical images. The idea is to create a ``master gold'' based on a consensus shape containing not just the outline of the segment but also the outlines of the internal zones if existent or relevant. To apply this new approach to accuracy measurement, we introduce the anatomy-aware extensions of both Dice coefficient and Jaccard index and investigate their effect using 500 synthetic prostate ultrasound images with 20 different segments for each image. We show that through anatomy-sensitive calculation of segmentation accuracy, namely by considering relevant anatomical zones, not only the measurement of individual users can change but also the ranking of users' segmentation skills may require reordering.

##### Abstract (translated by Google)
量化医学图像中的器官，组织类型和肿瘤的分割和手动描绘的准确度是一个必须的测量方法，其具有多个问题。所有精确度测量的一个主要缺点是忽略了给定片段内不同区域的解剖学意义或相关性。因此，现有的准确性度量标准测量给定片段与地面实况的重叠，而在片段内没有任何解剖学的区别。例如，如果我们将直肠壁或尿道括约肌理解为解剖学区域，那么当前的准确性测量方法在应用于评估前列腺节段的质量时忽略了它们的重要性。在本文中，我们提出了一种解剖学认知的医学图像分割准确度测量方案。这个想法是建立一个基于共识形状的“主金”，不仅包含分段的轮廓，还包括内部分区的轮廓，如果存在或相关的话。为了将这种新方法应用于准确性测量，我们引入了Dice系数和Jaccard指数的解剖学意义扩展，并且使用具有20个不同段的500个合成的前列腺超声图像来研究它们的效果。我们表明，通过对分割准确性的解剖敏感计算，即通过考虑相关的解剖区域，不仅个体用户的测量可以改变，而且用户的分割技能的排序可能需要重新排序。

##### URL
[https://arxiv.org/abs/1604.04678](https://arxiv.org/abs/1604.04678)

##### PDF
[https://arxiv.org/pdf/1604.04678](https://arxiv.org/pdf/1604.04678)

