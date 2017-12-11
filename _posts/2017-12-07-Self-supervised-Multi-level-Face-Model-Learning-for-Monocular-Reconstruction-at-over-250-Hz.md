---
layout: post
title: "Self-supervised Multi-level Face Model Learning for Monocular Reconstruction at over 250 Hz"
date: 2017-12-07 21:04:51
categories: arXiv_CV
tags: arXiv_CV Regularization Face CNN
author: Ayush Tewari, Michael Zollh&#xf6;fer, Pablo Garrido, Florian Bernard, Hyeongwoo Kim, Patrick P&#xe9;rez, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
The reconstruction of dense 3D models of face geometry and appearance from a single image is highly challenging and ill-posed. To constrain the problem, many approaches rely on strong priors, such as parametric face models learned from limited 3D scan data. However, prior models restrict generalization of the true diversity in facial geometry, skin reflectance and illumination. To alleviate this problem, we present the first approach that jointly learns 1) a regressor for face shape, expression, reflectance and illumination on the basis of 2) a concurrently learned parametric face model. Our multi-level face model combines the advantage of 3D Morphable Models for regularization with the out-of-space generalization of a learned corrective space. We train end-to-end on in-the-wild images without dense annotations by fusing a convolutional encoder with a differentiable expert-designed renderer and a self-supervised training loss, both defined at multiple detail levels. Our approach compares favorably to the state-of-the-art in terms of reconstruction quality, better generalizes to real world faces, and runs at over 250 Hz.

##### Abstract (translated by Google)
从单个图像重构面部几何形状和外观的密集三维模型是非常具有挑战性和不合适的。为了约束这个问题，许多方法依赖于强有力的先验，例如从有限的三维扫描数据中学习的参数人脸模型。然而，先前的模型限制了面部几何，皮肤反射和照明的真实多样性的泛化。为了缓解这个问题，我们提出了第一种方法，在2）同时学习的参数人脸模型的基础上共同学习1）面部形状，表情，反射和照明的回归。我们的多级人脸模型结合了正则化的三维形变模型的优点和学习修正空间的空间外推广。我们通过融合卷积编码器和专门设计的可渲染渲染器以及自我监督训练损失（都在多个细节层次上定义），在没有密集注释的野外图像上进行端对端培训。我们的方法与重建质量方面的最新技术相比，更好地推广到现实世界中，运行频率超过250 Hz。

##### URL
[http://arxiv.org/abs/1712.02859](http://arxiv.org/abs/1712.02859)

##### PDF
[http://arxiv.org/pdf/1712.02859](http://arxiv.org/pdf/1712.02859)

