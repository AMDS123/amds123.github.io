---
layout: post
title: "Circle detection using isosceles triangles sampling"
date: 2015-11-02 11:55:30
categories: arXiv_CV
tags: arXiv_CV Detection
author: Hanqing Zhang, Krister Wiklund, Magnus Andersson
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of circular objects in digital images is an important problem in several vision applications. Circle detection using randomized sampling has been developed in recent years to reduce the computational intensity. Randomized sampling, however, is sensitive to noise that can lead to reduced accuracy and false-positive candidates. This paper presents a new circle detection method based upon randomized isosceles triangles sampling to improve the robustness of randomized circle detection in noisy conditions. It is shown that the geometrical property of isosceles triangles provide a robust criterion to find relevant edge pixels and thereby efficiently provide an estimation of the circle center and radii. The estimated results given by the isosceles triangles sampling from each connected component of edge map were analyzed using a simple clustering approach for efficiency. To further improve on the accuracy we applied a two-step refinement process using chords and linear error compensation with gradient information of the edge pixels. Extensive experiments using both synthetic and real images were presented and results were compared to leading state-of-the-art algorithms and showed that the proposed algorithm: are efficient in finding circles with a low number of iterations; has high rejection rate of false-positive circle candidates; and has high robustness against noise, making it adaptive and useful in many vision applications.

##### Abstract (translated by Google)
在数字图像中检测圆形物体是几个视觉应用中的重要问题。使用随机采样的圆检测已经在近年来发展起来，以降低计算强度。然而，随机抽样对噪声很敏感，可能会导致准确性降低和假阳性候选人。本文提出了一种基于随机等腰三角形抽样的圆检测方法，以提高噪声条件下随机圆检测的鲁棒性。结果表明，等腰三角形的几何性质为找到相关的边缘像素提供了鲁棒的准则，从而有效地提供了圆心和半径的估计。使用简单的聚类方法来分析从边缘映射的每个连通分量的等腰三角形采样得到的估计结果以获得效率。为了进一步提高精度，我们应用了两步细化过程，使用和弦和线性误差补偿以及边缘像素的梯度信息。提出了使用合成图像和真实图像的大量实验，并将结果与​​领先的最先进的算法进行比较，并且表明所提出的算法：有效地找到具有低迭代次数的圆;对假阳性候选人的拒绝率高;并具有较高的抗噪声能力，使其适用于许多视觉应用。

##### URL
[https://arxiv.org/abs/1511.00461](https://arxiv.org/abs/1511.00461)

##### PDF
[https://arxiv.org/pdf/1511.00461](https://arxiv.org/pdf/1511.00461)

