---
layout: post
title: "MPTV: Matching Pursuit Based Total Variation Minimization for Image Deconvolution"
date: 2018-10-12 10:07:05
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Dong Gong, Mingkui Tan, Qinfeng Shi, Anton van den Hengel, Yanning Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Total variation (TV) regularization has proven effective for a range of computer vision tasks through its preferential weighting of sharp image edges. Existing TV-based methods, however, often suffer from the over-smoothing issue and solution bias caused by the homogeneous penalization. In this paper, we consider addressing these issues by applying inhomogeneous regularization on different image components. We formulate the inhomogeneous TV minimization problem as a convex quadratic constrained linear programming problem. Relying on this new model, we propose a matching pursuit based total variation minimization method (MPTV), specifically for image deconvolution. The proposed MPTV method is essentially a cutting-plane method, which iteratively activates a subset of nonzero image gradients, and then solves a subproblem focusing on those activated gradients only. Compared to existing methods, MPTV is less sensitive to the choice of the trade-off parameter between data fitting and regularization. Moreover, the inhomogeneity of MPTV alleviates the over-smoothing and ringing artifacts, and improves the robustness to errors in blur kernel. Extensive experiments on different tasks demonstrate the superiority of the proposed method over the current state-of-the-art.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05438](https://arxiv.org/abs/1810.05438)

##### PDF
[https://arxiv.org/pdf/1810.05438](https://arxiv.org/pdf/1810.05438)

