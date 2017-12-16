---
layout: post
title: "Interpretable Transformations with Encoder-Decoder Networks"
date: 2017-10-19 18:28:15
categories: arXiv_CV
tags: arXiv_CV Classification Relation
author: Daniel E. Worrall, Stephan J. Garbin, Daniyar Turmukhambetov, Gabriel J. Brostow
mathjax: true
---

* content
{:toc}

##### Abstract
Deep feature spaces have the capacity to encode complex transformations of their input data. However, understanding the relative feature-space relationship between two transformed encoded images is difficult. For instance, what is the relative feature space relationship between two rotated images? What is decoded when we interpolate in feature space? Ideally, we want to disentangle confounding factors, such as pose, appearance, and illumination, from object identity. Disentangling these is difficult because they interact in very nonlinear ways. We propose a simple method to construct a deep feature space, with explicitly disentangled representations of several known transformations. A person or algorithm can then manipulate the disentangled representation, for example, to re-render an image with explicit control over parameterized degrees of freedom. The feature space is constructed using a transforming encoder-decoder network with a custom feature transform layer, acting on the hidden representations. We demonstrate the advantages of explicit disentangling on a variety of datasets and transformations, and as an aid for traditional tasks, such as classification.

##### Abstract (translated by Google)
深特征空间具有对输入数据的复杂变换进行编码的能力。然而，理解两个变换的编码图像之间的相对特征空间关系是困难的。例如，两个旋转图像之间的相对特征空间关系是什么？当我们在特征空间内插时解码什么？理想情况下，我们想要从混乱的因素，如姿态，外观和照明，从物体的身份。解开这些是非常困难的，因为它们以非常非线性的方式相互作用。我们提出了一个简单的方法来构建一个深层特征空间，并且明确地解开了几个已知变换的表示。然后人或算法可以操纵解开的表示，例如，通过对参数化自由度的显式控制来重新呈现图像。特征空间是使用具有自定义特征变换层的变换编码器 - 解码器网络构建的，作用于隐藏的表示。我们展示了对各种数据集和转换进行显式分解的优点，并且作为传统任务（如分类）的辅助手段。

##### URL
[https://arxiv.org/abs/1710.07307](https://arxiv.org/abs/1710.07307)

##### PDF
[https://arxiv.org/pdf/1710.07307](https://arxiv.org/pdf/1710.07307)

