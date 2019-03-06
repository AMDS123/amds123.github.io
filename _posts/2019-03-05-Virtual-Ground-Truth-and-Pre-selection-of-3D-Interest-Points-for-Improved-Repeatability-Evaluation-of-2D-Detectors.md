---
layout: post
title: "Virtual Ground Truth, and Pre-selection of 3D Interest Points for Improved Repeatability Evaluation of 2D Detectors"
date: 2019-03-05 14:03:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Simon R Lang, Martin H Luerssen, David M Powers
mathjax: true
---

* content
{:toc}

##### Abstract
In Computer Vision, finding simple features is performed using classifiers called interest point (IP) detectors, which are often utilised to track features as the scene changes. For 2D based classifiers it has been intuitive to measure repeated point reliability using 2D metrics given the difficulty to establish ground truth beyond 2D. The aim is to bridge the gap between 2D classifiers and 3D environments, and improve performance analysis of 2D IP classification on 3D objects. This paper builds on existing work with 3D scanned and artificial models to test conventional 2D feature detectors with the assistance of virtualised 3D scenes. Virtual space depth is leveraged in tests to perform pre-selection of closest repeatable points in both 2D and 3D contexts before repeatability is measured. This more reliable ground truth is used to analyse testing configurations with a singular and 12 model dataset across affine transforms in x, y and z rotation, as well as x,y scaling with 9 well known IP detectors. The virtual scene's ground truth demonstrates that 3D pre-selection eliminates a large portion of false positives that are normally considered repeated in 2D configurations. The results indicate that 3D virtual environments can provide assistance in comparing the performance of conventional detectors when extending their applications to 3D environments, and can result in better classification of features when testing prospective classifiers' performance. A ROC based informedness measure also highlights tradeoffs in 2D/3D performance compared to conventional repeatability measures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01828](https://arxiv.org/abs/1903.01828)

##### PDF
[https://arxiv.org/pdf/1903.01828](https://arxiv.org/pdf/1903.01828)

