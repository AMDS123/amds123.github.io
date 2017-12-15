---
layout: post
title: "Active Mean Fields for Probabilistic Image Segmentation: Connections with Chan-Vese and Rudin-Osher-Fatemi Models"
date: 2016-10-04 23:10:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative
author: Marc Niethammer, Kilian M. Pohl, Firdaus Janoos, William M. Wells III
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation is a fundamental task for extracting semantically meaningful regions from an image. The goal of segmentation algorithms is to accurately assign object labels to each image location. However, image-noise, shortcomings of algorithms, and image ambiguities cause uncertainty in label assignment. Estimating the uncertainty in label assignment is important in multiple application domains, such as segmenting tumors from medical images for radiation treatment planning. One way to estimate these uncertainties is through the computation of posteriors of Bayesian models, which is computationally prohibitive for many practical applications. On the other hand, most computationally efficient methods fail to estimate label uncertainty. We therefore propose in this paper the Active Mean Fields (AMF) approach, a technique based on Bayesian modeling that uses a mean-field approximation to efficiently compute a segmentation and its corresponding uncertainty. Based on a variational formulation, the resulting convex model combines any label-likelihood measure with a prior on the length of the segmentation boundary. A specific implementation of that model is the Chan-Vese segmentation model (CV), in which the binary segmentation task is defined by a Gaussian likelihood and a prior regularizing the length of the segmentation boundary. Furthermore, the Euler-Lagrange equations derived from the AMF model are equivalent to those of the popular Rudin-Osher-Fatemi (ROF) model for image denoising. Solutions to the AMF model can thus be implemented by directly utilizing highly-efficient ROF solvers on log-likelihood ratio fields. We qualitatively assess the approach on synthetic data as well as on real natural and medical images. For a quantitative evaluation, we apply our approach to the icgbench dataset.

##### Abstract (translated by Google)
分割是从图像中提取语义上有意义的区域的基本任务。分割算法的目标是准确地为每个图像位置分配对象标签。然而，图像噪声，算法的缺点和图像模糊会导致标签分配的不确定性。估计标签分配中的不确定性在多个应用领域中是重要的，例如从用于放射治疗计划的医学图像中分割肿瘤。估计这些不确定性的一种方法是通过贝叶斯模型的后验计算，这在许多实际应用中在计算上是禁止的。另一方面，大多数计算有效的方法不能估计标签的不确定性。因此，我们在本文中提出了主动均值场（AMF）方法，一种基于贝叶斯建模的技术，该技术使用平均场近似来高效地计算分割及其相应的不确定性。基于变分公式，所得到的凸模型将任何标签可能性测度与分割边界长度上的先验相结合。该模型的具体实现是Chan-Vese分割模型（CV），其中二进制分割任务由高斯似然定义并且先验分割边界的长度。此外，由AMF模型导出的欧拉 - 拉格朗日方程与用于图像去噪的Rudin-Osher-Fatemi（ROF）模型相当。 AMF模型的解决方案因此可以通过在对数似然比字段上直接使用高效的ROF求解器来实现。我们定性评估合成数据的方法以及真实的自然和医学图像。对于定量评估，我们将我们的方法应用于icgbench数据集。

##### URL
[https://arxiv.org/abs/1501.05680](https://arxiv.org/abs/1501.05680)

##### PDF
[https://arxiv.org/pdf/1501.05680](https://arxiv.org/pdf/1501.05680)

