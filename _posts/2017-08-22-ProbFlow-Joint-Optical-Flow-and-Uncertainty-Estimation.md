---
layout: post
title: "ProbFlow: Joint Optical Flow and Uncertainty Estimation"
date: 2017-08-22 06:40:32
categories: arXiv_CV
tags: arXiv_CV Inference
author: Anne S. Wannenwetsch, Margret Keuper, Stefan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
Optical flow estimation remains challenging due to untextured areas, motion boundaries, occlusions, and more. Thus, the estimated flow is not equally reliable across the image. To that end, post-hoc confidence measures have been introduced to assess the per-pixel reliability of the flow. We overcome the artificial separation of optical flow and confidence estimation by introducing a method that jointly predicts optical flow and its underlying uncertainty. Starting from common energy-based formulations, we rely on the corresponding posterior distribution of the flow given the images. We derive a variational inference scheme based on mean field, which incorporates best practices from energy minimization. An uncertainty measure is obtained along the flow at every pixel as the (marginal) entropy of the variational distribution. We demonstrate the flexibility of our probabilistic approach by applying it to two different energies and on two benchmarks. We not only obtain flow results that are competitive with the underlying energy minimization approach, but also a reliable uncertainty measure that significantly outperforms existing post-hoc approaches.

##### Abstract (translated by Google)
由于无纹理区域，运动边界，遮挡等，光流估计仍然具有挑战性。因此，整个图像的估计流量不是同样可靠的。为此，引入了事后置信度度量来评估流程的每像素可靠性。我们通过引入联合预测光流和其不确定性的方法来克服光流和置信估计的人为分离。从普通的基于能量的公式出发，我们依赖于给定图像的相应的后验分布。我们推导出基于平均场的变分推理方案，其结合了能量最小化的最佳实践。沿着每个像素处的流动获得不确定性度量作为变分布的（边际）熵。我们通过将它应用于两种不同的能量和两个基准来证明我们的概率方法的灵活性。我们不仅获得与潜在的能量最小化方法相比具有竞争力的流量结果，而且还获得了明显优于现有的事后方法的可靠的不确定性度量。

##### URL
[https://arxiv.org/abs/1708.06509](https://arxiv.org/abs/1708.06509)

##### PDF
[https://arxiv.org/pdf/1708.06509](https://arxiv.org/pdf/1708.06509)

