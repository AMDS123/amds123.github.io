---
layout: post
title: "Kidney and Kidney Tumor Segmentation using a Logical Ensemble of U-nets with Volumetric Validation"
date: 2019-08-07 13:28:26
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Detection
author: Jamie A. O&#x27;Reilly, Manas Sangworasil, Takenobu Matsuura
mathjax: true
---

* content
{:toc}

##### Abstract
Automated medical image segmentation is a priority research area for computational methods. In particular, detection of cancerous tumors represents a current challenge in this area with potential for real-world impact. This paper describes a method developed in response to the 2019 Kidney Tumor Segmentation Challenge (KiTS19). Axial computed tomography (CT) scans from 210 kidney cancer patients were used to develop and evaluate this automatic segmentation method based on a logical ensemble of fully-convolutional network (FCN) architectures, followed by volumetric validation. Data was pre-processed using conventional computer vision techniques, thresholding, histogram equalization, morphological operations, centering, zooming and resizing. Three binary FCN segmentation models were trained to classify kidney and tumor (2), and only tumor (1), respectively. Model output images were stacked and volumetrically validated to produce the final segmentation for each patient scan. The average F1 score from kidney and tumor pixel classifications was calculated as 0.6758 using preprocessed images and annotations; although restoring to the original image format reduced this score. It remains to be seen how this compares to other solutions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02625](http://arxiv.org/abs/1908.02625)

##### PDF
[http://arxiv.org/pdf/1908.02625](http://arxiv.org/pdf/1908.02625)

