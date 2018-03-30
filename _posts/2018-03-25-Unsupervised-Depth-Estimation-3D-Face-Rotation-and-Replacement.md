---
layout: post
title: "Unsupervised Depth Estimation, 3D Face Rotation and Replacement"
date: 2018-03-25 05:07:11
categories: arXiv_CV
tags: arXiv_CV Adversarial Face
author: Joel Ruben Antony Moniz, Christopher Beckham, Simon Rajotte, Sina Honari, Christopher Pal
mathjax: true
---

* content
{:toc}

##### Abstract
We present an unsupervised approach for learning to estimate three dimensional (3D) facial structure from a single image while also predicting 3D viewpoint transformations that match a desired pose and facial geometry. We achieve this by inferring the depth of facial key-points in an input image in an unsupervised way. We show how it is possible to use these depths as intermediate computations within a new backpropable loss to predict the parameters of a 3D affine transformation matrix that maps inferred 3D key-points of an input face to corresponding 2D key-points on a desired target facial geometry or pose. Our resulting approach can therefore be used to infer plausible 3D transformations from one face pose to another, allowing faces to be frontalized, trans- formed into 3D models or even warped to another pose and facial geometry. Lastly, we identify certain shortcomings with our formulation, and explore adversarial image translation techniques as a post-processing step. Correspondingly, we explore several adversarial image transformation methods which allow us to re-synthesize complete head shots for faces re-targeted to different poses as well as repair images resulting from face replacements across identities.

##### Abstract (translated by Google)
我们提出了一种无监督方法，用于学习从单个图像估计三维（3D）面部结构，同时还预测与所需姿势和面部几何相匹配的3D视点变换。我们通过以无监督的方式推断输入图像中面部关键点的深度来实现这一点。我们展示了如何使用这些深度作为新的后退损失内的中间计算来预测3D仿射变换矩阵的参数，该3D仿射变换矩阵将输入面的推断的3D关键点映射到期望的目标面部上的对应的2D关键点几何或姿势。因此，我们所得到的方法可用于推断从一个人脸姿势到另一个人脸姿势的合理3D变换，允许人脸正面化，转换成3D模型，甚至翘曲到另一个姿势和面部几何体。最后，我们确定了我们的配方的某些缺点，并探讨对抗图像翻译技术作为后处理步骤。相应地，我们探索了几种对抗性图像转换方法，这些方法允许我们重新合成面向不同姿势的面部的完整头部照片，并修复由身份替换面部导致的图像。

##### URL
[https://arxiv.org/abs/1803.09202](https://arxiv.org/abs/1803.09202)

##### PDF
[https://arxiv.org/pdf/1803.09202](https://arxiv.org/pdf/1803.09202)

