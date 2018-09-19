---
layout: post
title: "Multiple Combined Constraints for Image Stitching"
date: 2018-09-18 13:34:25
categories: arXiv_CV
tags: arXiv_CV
author: Kai Chen, Jingmin Tu, Binbin Xiang, Li Li, Jian Yao
mathjax: true
---

* content
{:toc}

##### Abstract
Several approaches to image stitching use different constraints to estimate the motion model between image pairs. These constraints can be roughly divided into two categories: geometric constraints and photometric constraints. In this paper, geometric and photometric constraints are combined to improve the alignment quality, which is based on the observation that these two kinds of constraints are complementary. On the one hand, geometric constraints (e.g., point and line correspondences) are usually spatially biased and are insufficient in some extreme scenes, while photometric constraints are always evenly and densely distributed. On the other hand, photometric constraints are sensitive to displacements and are not suitable for images with large parallaxes, while geometric constraints are usually imposed by feature matching and are more robust to handle parallaxes. The proposed method therefore combines them together in an efficient mesh-based image warping framework. It achieves better alignment quality than methods only with geometric constraints, and can handle larger parallax than photometric-constraint-based method. Experimental results on various images illustrate that the proposed method outperforms representative state-of-the-art image stitching methods reported in the literature.

##### Abstract (translated by Google)
几种图像拼接方法使用不同的约束来估计图像对之间的运动模型。这些约束可以大致分为两类：几何约束和光度约束。在本文中，几何和光度约束相结合，以提高对齐质量，这是基于观察这两种约束是互补的。一方面，几何约束（例如，点和线对应）通常在空间上偏向并且在一些极端场景中不足，而光度约束总是均匀且密集地分布。另一方面，光度约束对位移敏感并且不适合具有大视差的图像，而几何约束通常由特征匹配强加并且对于处理视差更加鲁棒。因此，所提出的方法在有效的基于网格的图像变形框架中将它们组合在一起。与仅采用几何约束的方法相比，它实现了更好的对准质量，并且可以处理比基于光度约束的方法更大的视差。各种图像的实验结果表明，所提出的方法优于文献中报道的代表性的现有技术图像拼接方法。

##### URL
[https://arxiv.org/abs/1809.06706](https://arxiv.org/abs/1809.06706)

##### PDF
[https://arxiv.org/pdf/1809.06706](https://arxiv.org/pdf/1809.06706)

