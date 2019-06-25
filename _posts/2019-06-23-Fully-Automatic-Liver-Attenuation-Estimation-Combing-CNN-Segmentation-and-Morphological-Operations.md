---
layout: post
title: "Fully Automatic Liver Attenuation Estimation Combing CNN Segmentation and Morphological Operations"
date: 2019-06-23 04:00:32
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative
author: Yuankai Huo, James G. Terry, Jiachen Wang, Sangeeta Nair, Thomas A. Lasko, Barry I. Freedman, J. Jeffery Carr, Bennett A. Landman
mathjax: true
---

* content
{:toc}

##### Abstract
Manually tracing regions of interest (ROIs) within the liver is the de facto standard method for measuring liver attenuation on computed tomography (CT) in diagnosing nonalcoholic fatty liver disease (NAFLD). However, manual tracing is resource intensive. To address these limitations and to expand the availability of a quantitative CT measure of hepatic steatosis, we propose the automatic liver attenuation ROI-based measurement (ALARM) method for automated liver attenuation estimation. The ALARM method consists of two major stages: (1) deep convolutional neural network (DCNN)-based liver segmentation and (2) automated ROI extraction. First, liver segmentation was achieved using our previously developed SS-Net. Then, a single central ROI (center-ROI) and three circles ROI (periphery-ROI) were computed based on liver segmentation and morphological operations. The ALARM method is available as an open source Docker container (https://github.com/MASILab/ALARM).246 subjects with 738 abdomen CT scans from the African American-Diabetes Heart Study (AA-DHS) were used for external validation (testing), independent from the training and validation cohort (100 clinically acquired CT abdominal scans).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09549](http://arxiv.org/abs/1906.09549)

##### PDF
[http://arxiv.org/pdf/1906.09549](http://arxiv.org/pdf/1906.09549)

