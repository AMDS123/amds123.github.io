---
layout: post
title: "Automatic Delineation of Kidney Region in DCE-MRI"
date: 2019-05-26 23:25:59
categories: arXiv_CV
tags: arXiv_CV
author: Santosh Tirunagari, Norman Poh, Kevin Wells, Miroslaw Bober, Isky Gorden, David Windridge
mathjax: true
---

* content
{:toc}

##### Abstract
Delineation of the kidney region in dynamic contrast-enhanced magnetic resonance Imaging (DCE-MRI) is required during post-acquisition analysis in order to quantify various aspects of renal function, such as filtration and perfusion or blood flow. However, this can be obfuscated by the Partial Volume Effect (PVE), caused due to the mixing of any single voxel with two or more signal intensities from adjacent regions such as liver region and other tissues. To avoid this problem, firstly, a kidney region of interest (ROI) needs to be defined for the analysis. A clinician may choose to select a region avoiding edges where PV mixing is likely to be significant. However, this approach is time-consuming and labour intensive. To address this issue, we present Dynamic Mode Decomposition (DMD) coupled with thresholding and blob analysis as a framework for automatic delineation of the kidney region. This method is first validated on synthetically generated data with ground-truth available and then applied to ten healthy volunteers' kidney DCE-MRI datasets. We found that the result obtained from our proposed framework is comparable to that of a human expert. For example, while our result gives an average Root Mean Square Error (RMSE) of 0.0097, the baseline achieves an average RMSE of 0.1196 across the 10 datasets. As a result, we conclude automatic modelling via DMD framework is a promising approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11387](https://arxiv.org/abs/1905.11387)

##### PDF
[https://arxiv.org/pdf/1905.11387](https://arxiv.org/pdf/1905.11387)

