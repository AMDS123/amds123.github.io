---
layout: post
title: "Trajectory Space Factorization for Deep Video-Based 3D Human Pose Estimation"
date: 2019-08-22 10:03:30
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN RNN Deep_Learning
author: Jiahao Lin, Gim Hee Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Existing deep learning approaches on 3d human pose estimation for videos are either based on Recurrent or Convolutional Neural Networks (RNNs or CNNs). However, RNN-based frameworks can only tackle sequences with limited frames because sequential models are sensitive to bad frames and tend to drift over long sequences. Although existing CNN-based temporal frameworks attempt to address the sensitivity and drift problems by concurrently processing all input frames in the sequence, the existing state-of-the-art CNN-based framework is limited to 3d pose estimation of a single frame from a sequential input. In this paper, we propose a deep learning-based framework that utilizes matrix factorization for sequential 3d human poses estimation. Our approach processes all input frames concurrently to avoid the sensitivity and drift problems, and yet outputs the 3d pose estimates for every frame in the input sequence. More specifically, the 3d poses in all frames are represented as a motion matrix factorized into a trajectory bases matrix and a trajectory coefficient matrix. The trajectory bases matrix is precomputed from matrix factorization approaches such as Singular Value Decomposition (SVD) or Discrete Cosine Transform (DCT), and the problem of sequential 3d pose estimation is reduced to training a deep network to regress the trajectory coefficient matrix. We demonstrate the effectiveness of our framework on long sequences by achieving state-of-the-art performances on multiple benchmark datasets. Our source code is available at: this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08289](https://arxiv.org/abs/1908.08289)

##### PDF
[https://arxiv.org/pdf/1908.08289](https://arxiv.org/pdf/1908.08289)

