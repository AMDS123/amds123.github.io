---
layout: post
title: "Fast PET Scan Tumor Segmentation using Superpixels, Principal Component Analysis and K-means Clustering"
date: 2017-10-18 00:19:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Yeman B. Hagos, Vu H. Minh, Saed Khawaldeh, Usama Pervaiz, Tajwar A. Aleef
mathjax: true
---

* content
{:toc}

##### Abstract
Positron Emission Tomography scan images are extensively used in radiotherapy planning, clinical diagnosis, assessment of growth and treatment of a tumor. These all rely on fidelity and speed of detection and delineation algorithm. Despite intensive research, segmentation remained a challenging problem due to the diverse image content, resolution, shape, and noise. This paper presents a fast positron emission tomography tumor segmentation method in which superpixels are extracted first from the input image. Principal component analysis is then applied on the superpixels and also on their average. Distance vector of each superpixel from the average is computed in principal components coordinate system. Finally, k-means clustering is applied on distance vector to recognize tumor and non-tumor superpixels. The proposed approach is implemented in MATLAB 2016 which resulted in an average Dice similarity of 84.2% on the dataset. Additionally, a very fast execution time was achieved as the number of superpixels and the size of distance vector on which clustering was done was very small compared to the number of raw pixels in dataset images.

##### Abstract (translated by Google)
正电子发射断层扫描图像广泛用于放疗计划，临床诊断，肿瘤生长和治疗的评估。这些都依赖于保真度和速度检测和描绘算法。尽管进行了深入的研究，但由于图像内容，分辨率，形状和噪声的多样性，分割仍然是一个挑战性的问题本文提出了一种快速的正电子发射断层扫描肿瘤分割方法，其中从输入图像中首先提取超像素。然后对超像素以及它们的平均值应用主分量分析。在主分量坐标系中计算每个超像素距离平均值的距离向量。最后，对距离向量应用k均值聚类来识别肿瘤和非肿瘤超像素。所提出的方法在MATLAB 2016中实现，导致数据集中的平均Dice相似度为84.2％。另外，与数据集图像中的原始像素的数量相比，超级像素的数量和进行聚类的距离矢量的大小非常小，所以实现了非常快的执行时间。

##### URL
[https://arxiv.org/abs/1710.08798](https://arxiv.org/abs/1710.08798)

##### PDF
[https://arxiv.org/pdf/1710.08798](https://arxiv.org/pdf/1710.08798)

