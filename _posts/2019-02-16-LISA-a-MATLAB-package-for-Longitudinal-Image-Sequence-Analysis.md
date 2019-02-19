---
layout: post
title: "LISA: a MATLAB package for Longitudinal Image Sequence Analysis"
date: 2019-02-16 17:50:19
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jang Ik Cho, Xiaofeng Wang, Yifan Xu, Jiayang Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Large sequences of images (or movies) can now be obtained on an unprecedented scale, which poses fundamental challenges to the existing image analysis techniques. The challenges include heterogeneity, (automatic) alignment, multiple comparisons, potential artifacts, and hidden noises. This paper introduces our MATLAB package, Longitudinal Image Sequence Analysis (LISA), as a one-stop ensemble of image processing and analysis tool for comparing a general class of images from either different times, sessions, or subjects. Given two contrasting sequences of images, the image processing in LISA starts with selecting a region of interest in two representative images, followed by automatic or manual segmentation and registration. Automatic segmentation de-noises an image using a mixture of Gaussian distributions of the pixel intensity values, while manual segmentation applies a user-chosen intensity cut-off value to filter out noises. Automatic registration aligns the contrasting images based on a mid-line regression whereas manual registration lines up the images along a reference line formed by two user-selected points. The processed images are then rendered for simultaneous statistical comparisons to generate D, S, T, and P-maps. The D map represents a curated difference of contrasting images, the S map is the non-parametrically smoothed differences, the T map presents the variance-adjusted, smoothed differences, and the P-map provides multiplicity-controlled p-values. These maps reveal the regions with significant differences due to either longitudinal, subject-specific, or treatment changes. A user can skip the image processing step to dive directly into the statistical analysis step if the images have already been processed. Hence, LISA offers flexibility in applying other image pre-processing tools. LISA also has a parallel computing option for high definition images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06131](http://arxiv.org/abs/1902.06131)

##### PDF
[http://arxiv.org/pdf/1902.06131](http://arxiv.org/pdf/1902.06131)

