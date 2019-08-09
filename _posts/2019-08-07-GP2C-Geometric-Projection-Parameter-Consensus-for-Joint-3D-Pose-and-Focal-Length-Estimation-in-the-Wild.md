---
layout: post
title: "GP2C: Geometric Projection Parameter Consensus for Joint 3D Pose and Focal Length Estimation in the Wild"
date: 2019-08-07 19:44:09
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Deep_Learning
author: Alexander Grabner, Peter M. Roth, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
We present a joint 3D pose and focal length estimation approach for object categories in the wild. In contrast to previous methods that predict 3D poses independently of the focal length or assume a constant focal length, we explicitly estimate and integrate the focal length into the 3D pose estimation. For this purpose, we combine deep learning techniques and geometric algorithms in a two-stage approach: First, we estimate an initial focal length and establish 2D-3D correspondences from a single RGB image using a deep network. Second, we recover 3D poses and refine the focal length by minimizing the reprojection error of the predicted correspondences. In this way, we exploit the geometric prior given by the focal length for 3D pose estimation. This results in two advantages: First, we achieve significantly improved 3D translation and 3D pose accuracy compared to existing methods. Second, our approach finds a geometric consensus between the individual projection parameters, which is required for precise 2D-3D alignment. We evaluate our proposed approach on three challenging real-world datasets (Pix3D, Comp, and Stanford) with different object categories and significantly outperform the state-of-the-art by up to 20% absolute in multiple different metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02809](http://arxiv.org/abs/1908.02809)

##### PDF
[http://arxiv.org/pdf/1908.02809](http://arxiv.org/pdf/1908.02809)

