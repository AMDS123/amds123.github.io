---
layout: post
title: "Preterm infants' limb-pose estimation from depth images using convolutional neural networks"
date: 2019-07-26 10:15:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation Tracking CNN
author: Sara Moccia, Lucia Migliorelli, Rocco Pietrini, Emanuele Frontoni
mathjax: true
---

* content
{:toc}

##### Abstract
Preterm infants' limb-pose estimation is a crucial but challenging task, which may improve patients' care and facilitate clinicians in infant's movements monitoring. Work in the literature either provides approaches to whole-body segmentation and tracking, which, however, has poor clinical value, or retrieve a posteriori limb pose from limb segmentation, increasing computational costs and introducing inaccuracy sources. In this paper, we address the problem of limb-pose estimation under a different point of view. We proposed a 2D fully-convolutional neural network for roughly detecting limb joints and joint connections, followed by a regression convolutional neural network for accurate joint and joint-connection position estimation. Joints from the same limb are then connected with a maximum bipartite matching approach. Our analysis does not require any prior modeling of infants' body structure, neither any manual interventions. For developing and testing the proposed approach, we built a dataset of four videos (video length = 90 s) recorded with a depth sensor in a neonatal intensive care unit (NICU) during the actual clinical practice, achieving median root mean square distance [pixels] of 10.790 (right arm), 10.542 (left arm), 8.294 (right leg), 11.270 (left leg) with respect to the ground-truth limb pose. The idea of estimating limb pose directly from depth images may represent a future paradigm for addressing the problem of preterm-infants' movement monitoring and offer all possible support to clinicians in NICUs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12949](http://arxiv.org/abs/1907.12949)

##### PDF
[http://arxiv.org/pdf/1907.12949](http://arxiv.org/pdf/1907.12949)

