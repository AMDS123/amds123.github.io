---
layout: post
title: "Unsupervised 3D Pose Estimation with Geometric Self-Supervision"
date: 2019-04-09 17:53:50
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Pose_Estimation
author: Ching-Hang Chen, Ambrish Tyagi, Amit Agrawal, Dylan Drover, Rohith MV, Stefan Stojanov, James M. Rehg
mathjax: true
---

* content
{:toc}

##### Abstract
We present an unsupervised learning approach to recover 3D human pose from 2D skeletal joints extracted from a single image. Our method does not require any multi-view image data, 3D skeletons, correspondences between 2D-3D points, or use previously learned 3D priors during training. A lifting network accepts 2D landmarks as inputs and generates a corresponding 3D skeleton estimate. During training, the recovered 3D skeleton is reprojected on random camera viewpoints to generate new "synthetic" 2D poses. By lifting the synthetic 2D poses back to 3D and re-projecting them in the original camera view, we can define self-consistency loss both in 3D and in 2D. The training can thus be self supervised by exploiting the geometric self-consistency of the lift-reproject-lift process. We show that self-consistency alone is not sufficient to generate realistic skeletons, however adding a 2D pose discriminator enables the lifter to output valid 3D poses. Additionally, to learn from 2D poses "in the wild", we train an unsupervised 2D domain adapter network to allow for an expansion of 2D data. This improves results and demonstrates the usefulness of 2D pose data for unsupervised 3D lifting. Results on Human3.6M dataset for 3D human pose estimation demonstrate that our approach improves upon the previous unsupervised methods by 30% and outperforms many weakly supervised approaches that explicitly use 3D data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04812](http://arxiv.org/abs/1904.04812)

##### PDF
[http://arxiv.org/pdf/1904.04812](http://arxiv.org/pdf/1904.04812)

