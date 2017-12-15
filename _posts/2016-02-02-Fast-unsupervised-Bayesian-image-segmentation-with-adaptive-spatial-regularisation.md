---
layout: post
title: "Fast unsupervised Bayesian image segmentation with adaptive spatial regularisation"
date: 2016-02-02 08:53:06
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Marcelo Pereyra, Steve McLaughlin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new Bayesian estimation technique for hidden Potts-Markov random fields with unknown regularisation parameters, with application to fast unsupervised K-class image segmentation. The technique is derived by first removing the regularisation parameter from the Bayesian model by marginalisation, followed by a small-variance-asymptotic (SVA) analysis in which the spatial regularisation and the integer-constrained terms of the Potts model are decoupled. The evaluation of this SVA Bayesian estimator is then relaxed into a problem that can be computed efficiently by iteratively solving a convex total-variation denoising problem and a least-squares clustering (K-means) problem, both of which can be solved straightforwardly, even in high-dimensions, and with parallel computing techniques. This leads to a fast fully unsupervised Bayesian image segmentation methodology in which the strength of the spatial regularisation is adapted automatically to the observed image during the inference procedure, and that can be easily applied in large 2D and 3D scenarios or in applications requiring low computing times. Experimental results on real images, as well as extensive comparisons with state-of-the-art algorithms, confirm that the proposed methodology offer extremely fast convergence and produces accurate segmentation results, with the important additional advantage of self-adjusting regularisation parameters.

##### Abstract (translated by Google)
本文提出了一种新的未知正则化参数的Potts-Markov随机场贝叶斯估计方法，并应用于快速无监督的K类图像分割。该技术首先通过边缘化从贝叶斯模型中去除正则化参数，然后进行小方差渐近（SVA）分析，其中将Potts模型的空间正则化和整数约束条件解耦。然后将这个SVA贝叶斯估计量的评估放宽成一个问题，通过迭代求解一个凸总变分去噪问题和一个最小二乘聚类（K-means）问题，这两个问题都可以被直接求解，高维度和并行计算技术。这导致了一种快速完全无监督的贝叶斯图像分割方法，其中在推理过程中空间正则化的强度自动适应于观察图像，并且可以容易地应用于大的2D和3D场景或需要低计算时间的应用。真实图像的实验结果以及与最先进算法的广泛比较证实了所提出的方法提供了极快的收敛性并产生精确的分割结果，并具有自调节正则化参数的重要附加优势。

##### URL
[https://arxiv.org/abs/1502.01400](https://arxiv.org/abs/1502.01400)

##### PDF
[https://arxiv.org/pdf/1502.01400](https://arxiv.org/pdf/1502.01400)

