---
layout: post
title: "Improved Workflow for Unsupervised Multiphase Image Segmentation"
date: 2017-10-26 12:58:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Quantitative
author: Brendan A. West, Taylor S. Hodgdon, Matthew D. Parno, Arnold J. Song
mathjax: true
---

* content
{:toc}

##### Abstract
Quantitative image analysis often depends on accurate classification of pixels through a segmentation process. However, imaging artifacts such as the partial volume effect and sensor noise complicate the classification process. These effects increase the pixel intensity variance of each constituent class, causing intensities from one class to overlap with another. This increased variance makes threshold based segmentation methods insufficient due to ambiguous overlap regions in the pixel intensity distributions. The class ambiguity becomes even more complex for systems with more than two constituents, such as unsaturated moist granular media. In this paper, we propose an image processing workflow that improves segmentation accuracy for multiphase systems. First, the ambiguous transition regions between classes are identified and removed, which allows for global thresholding of single-class regions. Then the transition regions are classified using a distance function, and finally both segmentations are combined into one classified image. This workflow includes three methodologies for identifying transition pixels and we demonstrate on a variety of synthetic images that these approaches are able to accurately separate the ambiguous transition pixels from the single-class regions. For situations with typical amounts of image noise, misclassification errors and area differences calculated between each class of the synthetic images and the resultant segmented images range from 0.69-1.48% and 0.01-0.74%, respectively, showing the segmentation accuracy of this approach. We demonstrate that we are able to accurately segment x-ray microtomography images of moist granular media using these computationally efficient methodologies.

##### Abstract (translated by Google)
定量图像分析通常依赖于通过分割过程对像素的精确分类。然而，诸如部分音量效应和传感器噪声之类的成像伪影使分类过程复杂化。这些效应增加了每个组分类别的像素强度变化，导致一个类别的强度与另一个类别的强度重叠。由于像素强度分布中的模糊重叠区域，这种增加的方差使得基于阈值的分割方法不足。对于含有两种以上成分的系统，如不饱和湿颗粒介质，类歧义变得更为复杂。在本文中，我们提出了一个图像处理工作流程，提高了多相系统的分割精度。首先，识别和去除类之间模糊的过渡区域，从而实现单类地区的全局阈值化。然后使用距离函数对过渡区域进行分类，最后将两个分割结果合并为一个分类图像。这个工作流程包括三种识别过渡像素的方法，我们在各种合成图像上演示这些方法能够准确地将单一类别区域中的模糊过渡像素分开。对于具有典型的图像噪声量的情况，在每类合成图像与合成分割图像之间计算的误分类误差和面积差异分别为0.69-1.48％和0.01-0.74％，显示了该方法的分割准确性。我们证明，我们能够使用这些计算有效的方法准确地分割湿颗粒介质的X射线显微摄影图像。

##### URL
[https://arxiv.org/abs/1710.09671](https://arxiv.org/abs/1710.09671)

##### PDF
[https://arxiv.org/pdf/1710.09671](https://arxiv.org/pdf/1710.09671)

