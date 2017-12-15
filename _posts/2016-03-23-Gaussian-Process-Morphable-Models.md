---
layout: post
title: "Gaussian Process Morphable Models"
date: 2016-03-23 16:19:29
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Face
author: Marcel Lüthi, Christoph Jud, Thomas Gerig, Thomas Vetter
mathjax: true
---

* content
{:toc}

##### Abstract
Statistical shape models (SSMs) represent a class of shapes as a normal distribution of point variations, whose parameters are estimated from example shapes. Principal component analysis (PCA) is applied to obtain a low-dimensional representation of the shape variation in terms of the leading principal components. In this paper, we propose a generalization of SSMs, called Gaussian Process Morphable Models (GPMMs). We model the shape variations with a Gaussian process, which we represent using the leading components of its Karhunen-Loeve expansion. To compute the expansion, we make use of an approximation scheme based on the Nystrom method. The resulting model can be seen as a continuous analogon of an SSM. However, while for SSMs the shape variation is restricted to the span of the example data, with GPMMs we can define the shape variation using any Gaussian process. For example, we can build shape models that correspond to classical spline models, and thus do not require any example data. Furthermore, Gaussian processes make it possible to combine different models. For example, an SSM can be extended with a spline model, to obtain a model that incorporates learned shape characteristics, but is flexible enough to explain shapes that cannot be represented by the SSM. We introduce a simple algorithm for fitting a GPMM to a surface or image. This results in a non-rigid registration approach, whose regularization properties are defined by a GPMM. We show how we can obtain different registration schemes,including methods for multi-scale, spatially-varying or hybrid registration, by constructing an appropriate GPMM. As our approach strictly separates modelling from the fitting process, this is all achieved without changes to the fitting algorithm. We show the applicability and versatility of GPMMs on a clinical use case, where the goal is the model-based segmentation of 3D forearm images.

##### Abstract (translated by Google)
统计形状模型（SSM）代表一类形状作为点变化的正态分布，其参数是从示例形状估计的。主成分分析（PCA）被应用来获得关于主要主成分的形状变化的低维表示。在本文中，我们提出了SSM的推广，称为高斯过程形变模型（GPMM）。我们使用高斯过程对形状变化进行建模，我们使用Karhunen-Loeve扩展的主要组件来表示形状变化。为了计算扩展，我们利用基于Nystrom方法的近似方案。由此产生的模型可以被看作是一个SSM的连续模拟。然而，对于SSM，形状变化仅限于示例数据的范围，使用GPMM，我们可以使用任何高斯过程来定义形状变化。例如，我们可以建立对应于经典样条模型的形状模型，因此不需要任何示例数据。而且，高斯过程可以组合不同的模型。例如，可以用样条模型扩展SSM，以获得结合了学习形状特征的模型，但是足够灵活以解释SSM不能表示的形状。我们介绍一个简单的算法来拟合GPMM到曲面或图像。这导致非刚性配准方法，其正则化属性由GPMM定义。我们展示了如何通过构建适当的GPMM来获得不同的注册方案，包括多尺度，空间变化或混合注册的方法。由于我们的方法严格地将建模与拟合过程分开，所以这一切都是在不改变拟合算法的情况下实现的。我们展示GPMM在临床使用案例中的适用性和多功能性，其中目标是三维前臂图像的基于模型的分割。

##### URL
[https://arxiv.org/abs/1603.07254](https://arxiv.org/abs/1603.07254)

##### PDF
[https://arxiv.org/pdf/1603.07254](https://arxiv.org/pdf/1603.07254)

