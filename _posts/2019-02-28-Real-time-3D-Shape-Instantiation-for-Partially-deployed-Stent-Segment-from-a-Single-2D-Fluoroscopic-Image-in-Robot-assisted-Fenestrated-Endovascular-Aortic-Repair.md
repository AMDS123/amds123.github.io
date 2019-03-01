---
layout: post
title: "Real-time 3D Shape Instantiation for Partially-deployed Stent Segment from a Single 2D Fluoroscopic Image in Robot-assisted Fenestrated Endovascular Aortic Repair"
date: 2019-02-28 14:06:36
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Jian-Qing Zheng, Xiao-Yun Zhou, Guang-Zhong Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In robot-assisted Fenestrated Endovascular Aortic Repair (FEVAR), accurate alignment of stent graft fenestrations or scallops with aortic branches is essential for establishing complete blood flow perfusion. Current navigation is largely based on 2D fluoroscopic images, which lacks 3D anatomical information, thus causing longer operation time as well as high risks of radiation exposure. Previously, 3D shape instantiation frameworks for real-time 3D shape reconstruction of fully-deployed or fully-compressed stent graft from a single 2D fluoroscopic image have been proposed for 3D navigation in robot-assisted FEVAR. However, these methods could not instantiate partially-deployed stent segments, as the 3D marker references are unknown. In this paper, an adapted Graph Convolutional Network (GCN) is proposed to predict 3D marker references from 3D fully-deployed markers. As original GCN is for classification, in this paper, the coarsening layers are removed and the softmax function at the network end is replaced with linear mapping for the regression task. The derived 3D and the 2D marker references are used to instantiate partially-deployed stent segment shape with the existing 3D shape instantiation framework. Validations were performed on three commonly used stent grafts and five patient-specific 3D printed aortic aneurysm phantoms. Comparable performances with average mesh distance errors of 1$\sim$3mm and average angular errors around 7degree were achieved.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11089](http://arxiv.org/abs/1902.11089)

##### PDF
[http://arxiv.org/pdf/1902.11089](http://arxiv.org/pdf/1902.11089)

