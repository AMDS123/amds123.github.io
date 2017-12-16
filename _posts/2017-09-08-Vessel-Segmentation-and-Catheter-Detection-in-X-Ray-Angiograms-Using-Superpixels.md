---
layout: post
title: "Vessel Segmentation and Catheter Detection in X-Ray Angiograms Using Superpixels"
date: 2017-09-08 15:22:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Quantitative Detection
author: Hamid R. Fazlali, Nader Karimi, S.M. Reza Soroushmehr, Shahram Shirani, Brahmajee.K. Nallamothu, Kevin R. Ward, Shadrokh Samavi, Kayvan Najarian
mathjax: true
---

* content
{:toc}

##### Abstract
Coronary artery disease (CAD) is the leading causes of death around the world. One of the most common imaging methods for diagnosing this disease is X-ray angiography. Diagnosing using these images is usually challenging due to non-uniform illumination, low contrast, presence of other body tissues, presence of catheter etc. These challenges make the diagnoses task of cardiologists tougher and more prone to misdiagnosis. In this paper we propose a new automated framework for coronary arteries segmentation, catheter detection and center-line extraction in x-ray angiography images. Our proposed segmentation method is based on superpixels. In this method at first three different superpixel scales are exploited and a measure for vesselness probability of each superpixel is determined. A majority voting is used for obtaining an initial segmentation map from these three superpixel scales. This initial segmentation is refined by finding the orthogonal line on each ridge pixel of vessel region. In this framework we use our catheter detection and tracking method which detects the catheter by finding its ridge in the first frame and traces in other frames by fitting a second order polynomial on it. Also we use the image ridges for extracting the coronary arteries centerlines. We evaluated our method qualitatively and quantitatively on two different challenging datasets and compared it with one of the previous well-known coronary arteries segmentation methods. Our method could detect the catheter and reduced the false positive rate in addition to achieving better segmentation results. The evaluation results prove that our method performs better in a much shorter time.

##### Abstract (translated by Google)
冠状动脉疾病（CAD）是世界各地死亡的主要原因。 X线血管造影是诊断这种疾病的最常见的成像方法之一。由于不均匀的照明，低对比度，其他身体组织的存在，导管的存在，使用这些图像进行诊断通常是具有挑战性的。这些挑战使得心脏病专家的诊断任务变得更加困难并且更易于误诊。在本文中，我们提出了一个新的自动化框架冠状动脉分割，导管检测和中心线提取的X射线血管造影图像。我们提出的分割方法是基于超像素。在该方法中，首先利用三个不同的超像素尺度，并确定每个超像素的血管概率的度量。多数投票用于从这三个超像素尺度获得初始分割图。该初始分割通过在血管区域的每个脊像素上找到正交线而被细化。在这个框架中，我们使用我们的导管检测和跟踪方法，通过在第一帧中找到其脊以及通过在其上拟合二阶多项式来跟踪其他帧中的导管来检测导管。此外，我们使用图像脊提取冠状动脉中心线。我们在两个不同的具有挑战性的数据集上定性和定量地评估了我们的方法，并将其与之前众所周知的冠状动脉分割方法之一进行了比较。我们的方法可以检测导管，并减少误报率，除了实现更好的分割结果。评估结果证明，我们的方法在更短的时间内表现更好。

##### URL
[https://arxiv.org/abs/1709.02741](https://arxiv.org/abs/1709.02741)

##### PDF
[https://arxiv.org/pdf/1709.02741](https://arxiv.org/pdf/1709.02741)

