---
layout: post
title: "Hubless keypoint-based 3D deformable groupwise registration"
date: 2019-05-06 09:57:37
categories: arXiv_CV
tags: arXiv_CV Optimization Detection Gradient_Descent
author: R&#xe9;mi Agier, S&#xe9;bastien Valette, Razmig K&#xe9;chichian, Laurent Fanton, R&#xe9;my Prost
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel algorithm for Fast Registration Of image Groups (FROG), applied to large 3D image groups. Our approach extracts 3D SURF keypoints from images, computes matched pairs of keypoints and registers the group by minimizing pair distances in a hubless way i.e. without computing any central mean image. Using keypoints significantly reduces the problem complexity compared to voxel-based approaches, and enables us to provide an in-core global optimization, similar to the Bundle Adjustment for 3D reconstruction. As we aim to register images of different patients, the matching step yields many outliers. Then we propose a new EM-weighting algorithm which efficiently discards outliers. Global optimization is carried out with a fast gradient descent algorithm. This allows our approach to robustly register large datasets. The result is a set of diffeomorphic half transforms which link the volumes together and can be subsequently exploited for computational anatomy and landmark detection. We show experimental results on whole-body CT scans, with groups of up to 103 volumes. On a benchmark based on anatomical landmarks, our algorithm compares favorably with the star-groupwise voxel-based ANTs and NiftyReg approaches while being much faster. We also discuss the limitations of our approach for lower resolution images such as brain MRI.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.03951](http://arxiv.org/abs/1809.03951)

##### PDF
[http://arxiv.org/pdf/1809.03951](http://arxiv.org/pdf/1809.03951)

