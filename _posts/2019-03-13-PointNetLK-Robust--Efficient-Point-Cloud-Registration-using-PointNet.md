---
layout: post
title: "PointNetLK: Robust & Efficient Point Cloud Registration using PointNet"
date: 2019-03-13 20:56:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning
author: Yasuhiro Aoki, Hunter Goforth, Rangaprasad Arun Srivatsan, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
PointNet has revolutionized how we think about representing point clouds. For classification and segmentation tasks, the approach and its subsequent extensions are state-of-the-art. To date, the successful application of PointNet to point cloud registration has remained elusive. In this paper we argue that PointNet itself can be thought of as a learnable "imaging" function. As a consequence, classical vision algorithms for image alignment can be applied on the problem - namely the Lucas &amp; Kanade (LK) algorithm. Our central innovations stem from: (i) how to modify the LK algorithm to accommodate the PointNet imaging function, and (ii) unrolling PointNet and the LK algorithm into a single trainable recurrent deep neural network. We describe the architecture, and compare its performance against state-of-the-art in common registration scenarios. The architecture offers some remarkable properties including: generalization across shape categories and computational efficiency - opening up new paths of exploration for the application of deep learning to point cloud registration. Code and videos are available at https://github.com/hmgoforth/PointNetLK.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05711](http://arxiv.org/abs/1903.05711)

##### PDF
[http://arxiv.org/pdf/1903.05711](http://arxiv.org/pdf/1903.05711)

