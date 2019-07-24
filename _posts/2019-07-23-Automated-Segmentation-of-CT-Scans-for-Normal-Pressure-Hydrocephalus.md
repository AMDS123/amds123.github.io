---
layout: post
title: "Automated Segmentation of CT Scans for Normal Pressure Hydrocephalus"
date: 2019-07-23 17:47:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Recognition
author: Angela Zhang, Po-Yu Kao, Ronald Sahyouni, Ashutosh Shelat, Jefferson Chen, B.S. Manjunath
mathjax: true
---

* content
{:toc}

##### Abstract
Normal Pressure Hydrocephalus (NPH) is one of the few reversible forms of dementia, Due to their low cost and versatility, Computed Tomography (CT) scans have long been used as an aid to help diagnose intracerebral anomalies such as NPH. However, no well-defined and effective protocol currently exists for the analysis of CT scan-based ventricular, cerebral mass and subarachnoid space volumes in the setting of NPH. The Evan's ratio, an approximation of the ratio of ventricle to brain volume using only one 2D slice of the scan, has been proposed but is not robust. Instead of manually measuring a 2-dimensional proxy for the ratio of ventricle volume to brain volume, this study proposes an automated method of calculating the brain volumes for better recognition of NPH from a radiological standpoint. The method first aligns the subject CT volume to a common space through an affine transformation, then uses a random forest classifier to mask relevant tissue types. A 3D morphological segmentation method is used to partition the brain volume, which in turn is used to train machine learning methods to classify the subjects into non-NPH vs. NPH based on volumetric information. The proposed algorithm has increased sensitivity compared to the Evan's ratio thresholding method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09088](http://arxiv.org/abs/1901.09088)

##### PDF
[http://arxiv.org/pdf/1901.09088](http://arxiv.org/pdf/1901.09088)

