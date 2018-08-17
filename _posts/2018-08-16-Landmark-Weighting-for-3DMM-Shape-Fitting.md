---
layout: post
title: "Landmark Weighting for 3DMM Shape Fitting"
date: 2018-08-16 09:59:03
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Optimization
author: Yu Yanga, Xiao-Jun Wu, Josef Kittler
mathjax: true
---

* content
{:toc}

##### Abstract
Human face is a 3D object with shape and surface texture. 3D Morphable Model (3DMM) is a powerful tool for reconstructing the 3D face from a single 2D face image. In the shape fitting process, 3DMM estimates the correspondence between 2D and 3D landmarks. Most traditional 3DMM fitting methods fail to reconstruct an accurate model because face shape fitting is a difficult non-linear optimization problem. In this paper we show that landmark weighting is instrumental to improve the accuracy of shape reconstruction and propose a novel 3D Morphable Model Fitting method. Different from previous works that treat all landmarks equally, we take into consideration the estimated errors for each pair of 2D and 3D corresponding landmarks. The landmark points are weighted in the optimization cost function based on these errors. Obviously, these landmarks have different semantics because they locate on different facial components. In the context of the solution of fitting is approximated, there are deviations in landmarks matching. However, these landmarks with different semantics have different effects on reconstructing 3D faces. Thus, it is necessary to consider each landmark individually. To our knowledge, we are the first to analyze each feature point for 3D face reconstruction by 3DMM. The weight is adaptive with the estimation residuals of landmarks. Experimental results show that the proposed method significantly reduces the reconstruction error and improves the authenticity of the 3D model expression.

##### Abstract (translated by Google)
人脸是具有形状和表面纹理的3D对象。 3D Morphable Model（3DMM）是一种用于从单个2D人脸图像重建3D人脸的强大工具。在形状拟合过程中，3DMM估计2D和3D地标之间的对应关系。大多数传统的3DMM拟合方法无法重建精确的模型，因为面部形状拟合是一个困难的非线性优化问题。在本文中，我们表明，地标加权有助于提高形状重建的准确性，并提出了一种新的3D可变模型拟合方法。与之前平等对待所有地标的作品不同，我们会考虑每对2D和3D对应地标的估计误差。基于这些误差在优化成本函数中对界标点进行加权。显然，这些地标具有不同的语义，因为它们位于不同的面部组件上。在近似拟合解的上下文中，在地标匹配中存在偏差。然而，具有不同语义的这些地标对于重建3D面部具有不同的效果。因此，有必要单独考虑每个地标。据我们所知，我们是第一个通过3DMM分析3D面部重建的每个特征点。权重适应于地标的估计残差。实验结果表明，该方法显着降低了重建误差，提高了三维模型表达的真实性。

##### URL
[http://arxiv.org/abs/1808.05399](http://arxiv.org/abs/1808.05399)

##### PDF
[http://arxiv.org/pdf/1808.05399](http://arxiv.org/pdf/1808.05399)

