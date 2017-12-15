---
layout: post
title: "Image stitching with perspective-preserving warping"
date: 2016-05-17 05:07:51
categories: arXiv_CV
tags: arXiv_CV
author: Tianzhu Xiang, Gui-Song Xia, Liangpei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Image stitching algorithms often adopt the global transformation, such as homography, and work well for planar scenes or parallax free camera motions. However, these conditions are easily violated in practice. With casual camera motions, variable taken views, large depth change, or complex structures, it is a challenging task for stitching these images. The global transformation model often provides dreadful stitching results, such as misalignments or projective distortions, especially perspective distortion. To this end, we suggest a perspective-preserving warping for image stitching, which spatially combines local projective transformations and similarity transformation. By weighted combination scheme, our approach gradually extrapolates the local projective transformations of the overlapping regions into the non-overlapping regions, and thus the final warping can smoothly change from projective to similarity. The proposed method can provide satisfactory alignment accuracy as well as reduce the projective distortions and maintain the multi-perspective view. Experiments on a variety of challenging images confirm the efficiency of the approach.

##### Abstract (translated by Google)
图像拼接算法通常采用单应性等全局变换，适用于平面场景或无视差的摄像机运动。但是，这些条件在实践中很容易被侵犯。随着相机的轻松运动，可变视角，较大的深度变化或复杂的结构，拼接这些图像是一项具有挑战性的任务。全局转换模型通常提供可怕的拼接结果，如失调或投影失真，特别是视角失真。为此，我们提出了一种保持图像拼接的视角保持翘曲，将空间上的局部投影变换和相似变换相结合。通过加权组合方案，我们的方法逐渐推断出重叠区域的局部投影变换为非重叠区域，从而使得最终变形能够从投影向相似性平滑过渡。所提出的方法可以提供令人满意的对准精度以及减少投影失真并保持多视角视图。对各种具有挑战性的图像进行实验证实了该方法的有效性。

##### URL
[https://arxiv.org/abs/1605.05019](https://arxiv.org/abs/1605.05019)

##### PDF
[https://arxiv.org/pdf/1605.05019](https://arxiv.org/pdf/1605.05019)

