---
layout: post
title: "A Gaussian mixture model representation of endmember variability in hyperspectral unmixing"
date: 2017-09-29 20:10:00
categories: arXiv_CV
tags: arXiv_CV
author: Yuan Zhou, Anand Rangarajan, Paul D. Gader
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral unmixing while considering endmember variability is usually performed by the normal compositional model (NCM), where the endmembers for each pixel are assumed to be sampled from unimodal Gaussian distributions. However, in real applications, the distribution of a material is often not Gaussian. In this paper, we use Gaussian mixture models (GMM) to represent the endmember variability. We show, given the GMM starting premise, that the distribution of the mixed pixel (under the linear mixing model) is also a GMM (and this is shown from two perspectives). The first perspective originates from the random variable transformation and gives a conditional density function of the pixels given the abundances and GMM parameters. With proper smoothness and sparsity prior constraints on the abundances, the conditional density function leads to a standard maximum a posteriori (MAP) problem which can be solved using generalized expectation maximization. The second perspective originates from marginalizing over the endmembers in the GMM, which provides us with a foundation to solve for the endmembers at each pixel. Hence, our model can not only estimate the abundances and distribution parameters, but also the distinct endmember set for each pixel. We tested the proposed GMM on several synthetic and real datasets, and showed its potential by comparing it to current popular methods.

##### Abstract (translated by Google)
考虑端元变异性的高光谱解混通常由正态成分模型（NCM）执行，其中每个像素的端元被假定为从单峰高斯分布采样。但是，在实际应用中，材料的分布通常不是高斯的。在本文中，我们使用高斯混合模型（GMM）来表示端元变异性。给定GMM开始前提，我们展示混合像素（在线性混合模型下）的分布也是GMM（这从两个角度来看）。第一个视角来源于随机变量变换，给出了给定丰度和GMM参数的像素的条件密度函数。由于在丰度约束条件下具有适当的平滑性和稀疏性，条件密度函数导致了一个标准的最大后验（MAP）问题，可以用广义的期望最大化来解决。第二个观点来源于对GMM中边缘成员的边缘化，这为我们解决每个像素的边缘成员提供了基础。因此，我们的模型不仅可以估计丰度和分布参数，而且可以为每个像素设置不同的端元。我们在几个合成的和真实的数据集上测试了所提出的GMM，并通过将其与当前流行的方法进行比较来显示其潜力。

##### URL
[https://arxiv.org/abs/1710.00075](https://arxiv.org/abs/1710.00075)

##### PDF
[https://arxiv.org/pdf/1710.00075](https://arxiv.org/pdf/1710.00075)

