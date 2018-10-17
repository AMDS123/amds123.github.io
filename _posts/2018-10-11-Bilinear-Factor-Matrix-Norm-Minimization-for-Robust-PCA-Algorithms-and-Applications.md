---
layout: post
title: "Bilinear Factor Matrix Norm Minimization for Robust PCA: Algorithms and Applications"
date: 2018-10-11 18:06:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Detection
author: Fanhua Shang, James Cheng, Yuanyuan Liu, Zhi-Quan Luo, Zhouchen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
The heavy-tailed distributions of corrupted outliers and singular values of all channels in low-level vision have proven effective priors for many applications such as background modeling, photometric stereo and image alignment. And they can be well modeled by a hyper-Laplacian. However, the use of such distributions generally leads to challenging non-convex, non-smooth and non-Lipschitz problems, and makes existing algorithms very slow for large-scale applications. Together with the analytic solutions to lp-norm minimization with two specific values of p, i.e., p=1/2 and p=2/3, we propose two novel bilinear factor matrix norm minimization models for robust principal component analysis. We first define the double nuclear norm and Frobenius/nuclear hybrid norm penalties, and then prove that they are in essence the Schatten-1/2 and 2/3 quasi-norms, respectively, which lead to much more tractable and scalable Lipschitz optimization problems. Our experimental analysis shows that both our methods yield more accurate solutions than original Schatten quasi-norm minimization, even when the number of observations is very limited. Finally, we apply our penalties to various low-level vision problems, e.g., text removal, moving object detection, image alignment and inpainting, and show that our methods usually outperform the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05186](https://arxiv.org/abs/1810.05186)

##### PDF
[https://arxiv.org/pdf/1810.05186](https://arxiv.org/pdf/1810.05186)

