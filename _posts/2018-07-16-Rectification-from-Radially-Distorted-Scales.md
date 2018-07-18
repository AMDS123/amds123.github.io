---
layout: post
title: "Rectification from Radially-Distorted Scales"
date: 2018-07-16 21:03:36
categories: arXiv_CV
tags: arXiv_CV
author: James Pritts, Zuzana Kukelova, Viktor Larsson, Ondrej Chum
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces the first minimal solvers that jointly estimate lens distortion and affine rectification from repetitions of rigidly transformed coplanar local features. The proposed solvers incorporate lens distortion into the camera model and extend accurate rectification to wide-angle images that contain nearly any type of coplanar repeated content. We demonstrate a principled approach to generating stable minimal solvers by the Grobner basis method, which is accomplished by sampling feasible monomial bases to maximize numerical stability. Synthetic and real-image experiments confirm that the solvers give accurate rectifications from noisy measurements when used in a RANSAC-based estimator. The proposed solvers demonstrate superior robustness to noise compared to the state-of-the-art. The solvers work on scenes without straight lines and, in general, relax the strong assumptions on scene content made by the state-of-the-art. Accurate rectifications on imagery that was taken with narrow focal length to near fish-eye lenses demonstrate the wide applicability of the proposed method. The method is fully automated, and the code is publicly available at https://github.com/prittjam/repeats.

##### Abstract (translated by Google)
本文介绍了第一个最小的求解器，它们通过重复刚性变换的共面局部特征来联合估计镜头失真和仿射校正。所提出的解算器将镜头失真结合到相机模型中，并将精确校正扩展到包含几乎任何类型的共面重复内容的广角图像。我们通过Grobner基方法证明了生成稳定最小解算器的原理方法，该方法是通过对可行的单项式基数进行采样以最大化数值稳定性来实现的。合成和实际图像实验证实，当在基于RANSAC的估算器中使用时，求解器可以从噪声测量中进行精确校正。与现有技术相比，所提出的求解器表现出优异的噪声鲁棒性。解算器在没有直线的场景上工作，并且通常放松对现有技术所做的场景内容的强烈假设。对窄焦距到近鱼眼镜头拍摄的图像进行精确校正，证明了该方法的广泛适用性。该方法是完全自动化的，代码可在https://github.com/prittjam/r​​epeats上公开获得。

##### URL
[http://arxiv.org/abs/1807.06110](http://arxiv.org/abs/1807.06110)

##### PDF
[http://arxiv.org/pdf/1807.06110](http://arxiv.org/pdf/1807.06110)

