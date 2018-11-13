---
layout: post
title: "A Progressively-trained Scale-invariant and Boundary-aware Deep Neural Network for the Automatic 3D Segmentation of Lung Lesions"
date: 2018-11-11 17:32:38
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Bo Zhou, Randolph Crawford, Belma Dogdas, Gregory Goldmacher, Antong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Volumetric segmentation of lesions on CT scans is important for many types of analysis, including lesion growth kinetic modeling in clinical trials and machine learning of radiomic features. Manual segmentation is laborious, and impractical for large-scale use. For routine clinical use, and in clinical trials that apply the Response Evaluation Criteria In Solid Tumors (RECIST), clinicians typically outline the boundaries of a lesion on a single slice to extract diameter measurements. In this work, we have collected a large-scale database, named LesionVis, with pixel-wise manual 2D lesion delineations on the RECIST-slices. To extend the 2D segmentations to 3D, we propose a volumetric progressive lesion segmentation (PLS) algorithm to automatically segment the 3D lesion volume from 2D delineations using a scale-invariant and boundary-aware deep convolutional network (SIBA-Net). The SIBA-Net copes with the size transition of a lesion when the PLS progresses from the RECIST-slice to the edge-slices, as well as when performing longitudinal assessment of lesions whose size change over multiple time points. The proposed PLS-SiBA-Net (P-SiBA) approach is assessed on the lung lesion cases from LesionVis. Our experimental results demonstrate that the P-SiBA approach achieves mean Dice similarity coefficients (DSC) of 0.81, which significantly improves 3D segmentation accuracy compared with the approaches proposed previously (highest mean DSC at 0.78 on LesionVis). In summary, by leveraging the limited 2D delineations on the RECIST-slices, P-SiBA is an effective semi-supervised approach to produce accurate lesion segmentations in 3D.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04437](http://arxiv.org/abs/1811.04437)

##### PDF
[http://arxiv.org/pdf/1811.04437](http://arxiv.org/pdf/1811.04437)

