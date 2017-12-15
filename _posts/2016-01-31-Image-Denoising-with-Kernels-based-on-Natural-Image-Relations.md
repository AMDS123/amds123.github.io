---
layout: post
title: "Image Denoising with Kernels based on Natural Image Relations"
date: 2016-01-31 10:02:14
categories: arXiv_CV
tags: arXiv_CV Regularization Relation
author: Valero Laparra, Juan Gutiérrez, Gustavo Camps-Valls, Jesús Malo
mathjax: true
---

* content
{:toc}

##### Abstract
A successful class of image denoising methods is based on Bayesian approaches working in wavelet representations. However, analytical estimates can be obtained only for particular combinations of analytical models of signal and noise, thus precluding its straightforward extension to deal with other arbitrary noise sources. In this paper, we propose an alternative non-explicit way to take into account the relations among natural image wavelet coefficients for denoising: we use support vector regression (SVR) in the wavelet domain to enforce these relations in the estimated signal. Since relations among the coefficients are specific to the signal, the regularization property of SVR is exploited to remove the noise, which does not share this feature. The specific signal relations are encoded in an anisotropic kernel obtained from mutual information measures computed on a representative image database. Training considers minimizing the Kullback-Leibler divergence (KLD) between the estimated and actual probability functions of signal and noise in order to enforce similarity. Due to its non-parametric nature, the method can eventually cope with different noise sources without the need of an explicit re-formulation, as it is strictly necessary under parametric Bayesian formalisms. Results under several noise levels and noise sources show that: (1) the proposed method outperforms conventional wavelet methods that assume coefficient independence, (2) it is similar to state-of-the-art methods that do explicitly include these relations when the noise source is Gaussian, and (3) it gives better numerical and visual performance when more complex, realistic noise sources are considered. Therefore, the proposed machine learning approach can be seen as a more flexible (model-free) alternative to the explicit description of wavelet coefficient relations for image denoising.

##### Abstract (translated by Google)
一类成功的图像去噪方法是基于小波表示的贝叶斯方法。然而，只有信号和噪声分析模型的特定组合才能获得分析估计值，从而排除了直接扩展来处理其他任意噪声源的问题。在本文中，我们提出了另一种非显式方法来考虑自然图像小波系数之间的关系去噪：我们在小波域中使用支持向量回归（SVR）在估计的信号中执行这些关系。由于系数之间的关系是特定于信号的，所以利用SVR的正则化特性去除不具有该特征的噪声。特定的信号关系被编码在从代表性图像数据库计算出来的互信息度量中获得的各向异性内核中。训练考虑最小化信号和噪声的估计和实际概率函数之间的Kullback-Leibler散度（KLD），以便强化相似性。由于其非参数性质，该方法最终可以处理不同的噪声源，而不需要明确的重新制定，因为在参数化贝叶斯形式中这是严格必要的。在一些噪声水平和噪声源下的结果表明：（1）所提出的方法优于传统的假设系数无关的小波方法，（2）与噪声时明确包含这些关系的最新方法类似信源是高斯信号，（3）当考虑到更复杂，更真实的噪声源时，它提供了更好的数字和视觉表现。因此，所提出的机器学习方法可被看作是用于图像去噪的小波系数关系的明确描述的更灵活（无模型）的替代方案。

##### URL
[https://arxiv.org/abs/1602.00217](https://arxiv.org/abs/1602.00217)

##### PDF
[https://arxiv.org/pdf/1602.00217](https://arxiv.org/pdf/1602.00217)

