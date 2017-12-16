---
layout: post
title: "Automatic Color Image Segmentation Using a Square Elemental Region-Based Seeded Region Growing and Merging Method"
date: 2017-11-26 09:19:05
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Hisashi Shimodaira
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an efficient automatic color image segmentation method using a seeded region growing and merging method based on square elemental regions. Our segmentation method consists of the three steps: generating seed regions, merging the regions, and applying a pixel-wise boundary determination algorithm to the resultant polygonal regions. The major features of our method are as follows: the use of square elemental regions instead of pixels as the processing unit, a seed generation method based on enhanced gradient values, a seed region growing method exploiting local gradient values, a region merging method using a similarity measure including a homogeneity distance based on Tsallis entropy, and a termination condition of region merging using an estimated desired number of regions. Using square regions as the processing unit substantially reduces the time complexity of the algorithm and makes the performance stable. The experimental results show that our method exhibits stable performance for a variety of natural images, including heavily textured areas, and produces good segmentation results using the same parameter values. The results of our method are fairly comparable to, and in some respects better than, those of existing algorithms.

##### Abstract (translated by Google)
本文提出了一种基于方形元素区域的种子区域生长和合并方法的高效自动彩色图像分割方法。我们的分割方法由三个步骤组成：生成种子区域，合并区域，以及将像素方式的边界确定算法应用于所得到的多边形区域。我们的方法的主要特征如下：使用方形元素区域而不是像素作为处理单元，基于增强梯度值的种子生成方法，利用局部梯度值的种子区域生长方法，使用包括基于Tsallis熵的同质距离的相似性度量以及使用估计的期望数量的区域的区域合并的终止条件。使用正方形区域作为处理单元，大大减少了算法的时间复杂度，使性能稳定。实验结果表明，我们的方法表现出对于各种自然图像，包括重纹理区域稳定的性能，并使用相同的参数值产生良好的分割结果。我们的方法的结果是可比的，在某些方面比现有的算法更好。

##### URL
[https://arxiv.org/abs/1711.09352](https://arxiv.org/abs/1711.09352)

##### PDF
[https://arxiv.org/pdf/1711.09352](https://arxiv.org/pdf/1711.09352)

