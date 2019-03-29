---
layout: post
title: "3D Whole Brain Segmentation using Spatially Localized Atlas Network Tiles"
date: 2019-03-28 17:40:32
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Quantitative
author: Yuankai Huo, Zhoubing Xu, Yunxi Xiong, Katherine Aboud, Prasanna Parvathaneni, Shunxing Bao, Camilo Bermudez, Susan M. Resnick, Laurie E. Cutting, Bennett A. Landman
mathjax: true
---

* content
{:toc}

##### Abstract
Detailed whole brain segmentation is an essential quantitative technique, which provides a non-invasive way of measuring brain regions from a structural magnetic resonance imaging (MRI). Recently, deep convolution neural network (CNN) has been applied to whole brain segmentation. However, restricted by current GPU memory, 2D based methods, downsampling based 3D CNN methods, and patch-based high-resolution 3D CNN methods have been the de facto standard solutions. 3D patch-based high resolution methods typically yield superior performance among CNN approaches on detailed whole brain segmentation (&gt;100 labels), however, whose performance are still commonly inferior compared with multi-atlas segmentation methods (MAS) due to the following challenges: (1) a single network is typically used to learn both spatial and contextual information for the patches, (2) limited manually traced whole brain volumes are available (typically less than 50) for training a network. In this work, we propose the spatially localized atlas network tiles (SLANT) method to distribute multiple independent 3D fully convolutional networks (FCN) for high-resolution whole brain segmentation. To address the first challenge, multiple spatially distributed networks were used in the SLANT method, in which each network learned contextual information for a fixed spatial location. To address the second challenge, auxiliary labels on 5111 initially unlabeled scans were created by multi-atlas segmentation for training. Since the method integrated multiple traditional medical image processing methods with deep learning, we developed a containerized pipeline to deploy the end-to-end solution. From the results, the proposed method achieved superior performance compared with multi-atlas segmentation methods, while reducing the computational time from &gt;30 hours to 15 minutes (https://github.com/MASILab/SLANTbrainSeg).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12152](http://arxiv.org/abs/1903.12152)

##### PDF
[http://arxiv.org/pdf/1903.12152](http://arxiv.org/pdf/1903.12152)

