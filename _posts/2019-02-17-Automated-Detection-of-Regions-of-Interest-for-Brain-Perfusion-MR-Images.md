---
layout: post
title: "Automated Detection of Regions of Interest for Brain Perfusion MR Images"
date: 2019-02-17 20:47:22
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative Detection
author: Svitlana M Alkhimova
mathjax: true
---

* content
{:toc}

##### Abstract
Images with abnormal brain anatomy produce problems for automatic segmentation techniques, and as a result poor ROI detection affects both quantitative measurements and visual assessment of perfusion data. This paper presents a new approach for fully automated and relatively accurate ROI detection from dynamic susceptibility contrast perfusion magnetic resonance and can therefore be applied excellently in the perfusion analysis. In the proposed approach the segmentation output is a binary mask of perfusion ROI that has zero values for air pixels, pixels that represent non-brain tissues, and cerebrospinal fluid pixels. The process of binary mask producing starts with extracting low intensity pixels by thresholding. Optimal low-threshold value is solved by obtaining intensity pixels information from the approximate anatomical brain location. Holes filling algorithm and binary region growing algorithm are used to remove falsely detected regions and produce region of only brain tissues. Further, CSF pixels extraction is provided by thresholding of high intensity pixels from region of only brain tissues. Each time-point image of the perfusion sequence is used for adjustment of CSF pixels location. The segmentation results were compared with the manual segmentation performed by experienced radiologists, considered as the reference standard for evaluation of proposed approach. On average of 120 images the segmentation results have a good agreement with the reference standard. All detected perfusion ROIs were deemed by two experienced radiologists as satisfactory enough for clinical use. The results show that proposed approach is suitable to be used for perfusion ROI detection from DSC head scans. Segmentation tool based on the proposed approach can be implemented as a part of any automatic brain image processing system for clinical use.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06323](http://arxiv.org/abs/1902.06323)

##### PDF
[http://arxiv.org/pdf/1902.06323](http://arxiv.org/pdf/1902.06323)

