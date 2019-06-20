---
layout: post
title: "Analytical Derivatives for Differentiable Renderer: 3D Pose Estimation by Silhouette Consistency"
date: 2019-06-19 01:34:12
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization Quantitative
author: Zaiqiang Wu, Wei Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Differentiable render is widely used in optimization-based 3D reconstruction which requires gradients from differentiable operations for gradient-based optimization. The existing differentiable renderers obtain the gradients of rendering via numerical technique which is of low accuracy and efficiency. Motivated by this fact, a differentiable mesh renderer with analytical gradients is proposed. The main obstacle of rasterization based rendering being differentiable is the discrete sampling operation. To make the rasterization differentiable, the pixel intensity is defined as a double integral over the pixel area and the integral is approximated by anti-aliasing with an average filter. Then the analytical gradients with respect to the vertices coordinates can be derived from the continuous definition of pixel intensity. To demonstrate the effectiveness and efficiency of the proposed differentiable renderer, experiments of 3D pose estimation by only multi-viewpoint silhouettes were conducted. The experimental results show that 3D pose estimation without 3D and 2D joints supervision is capable of producing competitive results both qualitatively and quantitatively. The experimental results also show that the proposed differentiable renderer is of higher accuracy and efficiency compared with previous method of differentiable renderer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07870](http://arxiv.org/abs/1906.07870)

##### PDF
[http://arxiv.org/pdf/1906.07870](http://arxiv.org/pdf/1906.07870)

