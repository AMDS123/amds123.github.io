---
layout: post
title: "Self-Supervised Surgical Tool Segmentation using Kinematic Information"
date: 2019-02-13 09:43:25
categories: arXiv_RO
tags: arXiv_RO Knowledge Segmentation Pose_Estimation CNN Optimization Classification
author: Cristian da Costa Rocha, Nicolas Padoy, Benoit Rosa
mathjax: true
---

* content
{:toc}

##### Abstract
Surgical tool segmentation in endoscopic images is the first step towards pose estimation and (sub-)task automation in challenging minimally invasive surgical operations. While many approaches in the literature have shown great results using modern machine learning methods such as convolutional neural networks, the main bottleneck lies in the acquisition of a large number of manually-annotated images for efficient learning. This is especially true in surgical context, where patient-to-patient differences impede the overall generalizability. In order to cope with this lack of annotated data, we propose a self-supervised approach in a robot-assisted context. To our knowledge, the proposed approach is the first to make use of the kinematic model of the robot in order to generate training labels. The core contribution of the paper is to propose an optimization method to obtain good labels for training despite an unknown hand-eye calibration and an imprecise kinematic model. The labels can subsequently be used for fine-tuning a fully-convolutional neural network for pixel-wise classification. As a result, the tool can be segmented in the endoscopic images without needing a single manually-annotated image. Experimental results on phantom and in vivo datasets obtained using a flexible robotized endoscopy system are very promising.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04810](http://arxiv.org/abs/1902.04810)

##### PDF
[http://arxiv.org/pdf/1902.04810](http://arxiv.org/pdf/1902.04810)

