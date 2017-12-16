---
layout: post
title: "Tracking Tensor Subspaces with Informative Random Sampling for Real-Time MR Imaging"
date: 2016-09-14 01:23:05
categories: arXiv_CV
tags: arXiv_CV Regularization GAN Tracking Optimization Relation
author: Morteza Mardani, Georgios B. Giannakis, Kamil Ugurbil
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic resonance imaging (MRI) nowadays serves as an important modality for diagnostic and therapeutic guidance in clinics. However, the {\it slow acquisition} process, the dynamic deformation of organs, as well as the need for {\it real-time} reconstruction, pose major challenges toward obtaining artifact-free images. To cope with these challenges, the present paper advocates a novel subspace learning framework that permeates benefits from parallel factor (PARAFAC) decomposition of tensors (multiway data) to low-rank modeling of temporal sequence of images. Treating images as multiway data arrays, the novel method preserves spatial structures and unravels the latent correlations across various dimensions by means of the tensor subspace. Leveraging the spatio-temporal correlation of images, Tykhonov regularization is adopted as a rank surrogate for a least-squares optimization program. Alteranating majorization minimization is adopted to develop online algorithms that recursively procure the reconstruction upon arrival of a new undersampled $k$-space frame. The developed algorithms are {\it provably convergent} and highly {\it parallelizable} with lightweight FFT tasks per iteration. To further accelerate the acquisition process, randomized subsampling policies are devised that leverage intermediate estimates of the tensor subspace, offered by the online scheme, to {\it randomly} acquire {\it informative} $k$-space samples. In a nutshell, the novel approach enables tracking motion dynamics under low acquisition rates `on the fly.' GPU-based tests with real {\it in vivo} MRI datasets of cardiac cine images corroborate the merits of the novel approach relative to state-of-the-art alternatives.

##### Abstract (translated by Google)
磁共振成像（MRI）如今是临床诊断和治疗指导的重要手段。然而，慢速采集过程，器官的动态变形以及对实时重建的需求，对获得无伪影的图像构成了巨大的挑战。为了应对这些挑战，本文提出了一种新颖的子空间学习框架，它渗透了从张量（多维数据）的并行因子（PARAFAC）分解到时间序列图像的低秩建模的好处。新方法将图像视为多维数据阵列，通过张量子空间保留空间结构，揭示不同维度的潜在相关性。利用图像的时空相关性，采用Tykhonov正则化作为最小二乘优化程序的等级替代。采用偏移最小化的方法来开发在线算法，在新的欠采样$ k $空间帧到达时递归地获得重构。所开发的算法是每次迭代的轻量级FFT任务，并且高度可并行化。为了进一步加速收购过程，我们设计了随机子采样策略，利用在线方案提供的张量子空间的中间估计{随机}获得{\ it信息} $ k $  - 空间样本。简而言之，这种新颖的方法能够实时跟踪低采集率下的运动动态。基于GPU的心脏电影图像真实体内MRI数据集的测试证实了新颖方法相对于最先进的替代方案的优点。

##### URL
[https://arxiv.org/abs/1609.04104](https://arxiv.org/abs/1609.04104)

##### PDF
[https://arxiv.org/pdf/1609.04104](https://arxiv.org/pdf/1609.04104)

