---
layout: post
title: "Dense 3D Face Correspondence"
date: 2019-08-15 06:32:44
categories: arXiv_CV
tags: arXiv_CV Sparse Face Quantitative Recognition Face_Recognition
author: Syed Zulqarnain Gilani, Ajmal Mian, Faisal Shafait, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
We present an algorithm that automatically establishes dense correspondences between a large number of 3D faces. Starting from automatically detected sparse correspondences on the outer boundary of 3D faces, the algorithm triangulates existing correspondences and expands them iteratively by matching points of distinctive surface curvature along the triangle edges. After exhausting keypoint matches, further correspondences are established by generating evenly distributed points within triangles by evolving level set geodesic curves from the centroids of large triangles. A deformable model (K3DM) is constructed from the dense corresponded faces and an algorithm is proposed for morphing the K3DM to fit unseen faces. This algorithm iterates between rigid alignment of an unseen face followed by regularized morphing of the deformable model. We have extensively evaluated the proposed algorithms on synthetic data and real 3D faces from the FRGCv2, Bosphorus, BU3DFE and UND Ear databases using quantitative and qualitative benchmarks. Our algorithm achieved dense correspondences with a mean localisation error of 1.28mm on synthetic faces and detected $14$ anthropometric landmarks on unseen real faces from the FRGCv2 database with 3mm precision. Furthermore, our deformable model fitting algorithm achieved 98.5% face recognition accuracy on the FRGCv2 and 98.6% on Bosphorus database. Our dense model is also able to generalize to unseen datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1410.5058](http://arxiv.org/abs/1410.5058)

##### PDF
[http://arxiv.org/pdf/1410.5058](http://arxiv.org/pdf/1410.5058)

