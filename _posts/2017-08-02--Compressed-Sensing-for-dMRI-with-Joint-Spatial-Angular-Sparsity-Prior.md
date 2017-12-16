---
layout: post
title: "-Compressed Sensing for dMRI with Joint Spatial-Angular Sparsity Prior"
date: 2017-08-02 18:36:57
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Evan Schwab, René Vidal, Nicolas Charon
mathjax: true
---

* content
{:toc}

##### Abstract
Advanced diffusion magnetic resonance imaging (dMRI) techniques, like diffusion spectrum imaging (DSI) and high angular resolution diffusion imaging (HARDI), remain underutilized compared to diffusion tensor imaging because the scan times needed to produce accurate estimations of fiber orientation are significantly longer. To accelerate DSI and HARDI, recent methods from compressed sensing (CS) exploit a sparse underlying representation of the data in the spatial and angular domains to undersample in the respective k- and q-spaces. State-of-the-art frameworks, however, impose sparsity in the spatial and angular domains separately and involve the sum of the corresponding sparse regularizers. In contrast, we propose a unified (k,q)-CS formulation which imposes sparsity jointly in the spatial-angular domain to further increase sparsity of dMRI signals and reduce the required subsampling rate. To efficiently solve this large-scale global reconstruction problem, we introduce a novel adaptation of the FISTA algorithm that exploits dictionary separability. We show on phantom and real HARDI data that our approach achieves significantly more accurate signal reconstructions than the state of the art while sampling only 2-4% of the (k,q)-space, allowing for the potential of new levels of dMRI acceleration.

##### Abstract (translated by Google)
与扩散张量成像相比，扩散光谱成像（DSI）和高角分辨率扩散成像（HARDI）等先进扩散磁共振成像（dMRI）技术仍然没有得到充分利用，因为精确估计纤维取向所需的扫描时间明显更长。为了加速DSI和HARDI，来自压缩感测（CS）的最近方法利用空间和角度域中的数据的稀疏底层表示来在各自的k空间和q空间中欠采样。然而，最先进的框架分别在空间和角度域上分别施加稀疏性，并涉及相应的稀疏规则化器的总和。相比之下，我们提出了统一的（k，q）-CS公式，在空间角域共同施加稀疏性，进一步提高dMRI信号的稀疏性，降低所需的子采样率。为了有效地解决这个大规模的全球重建问题，我们引入了一个新的适应FISTA算法，利用字典可分性。我们用幻像和真实的HARDI数据展示了我们的方法比现有技术获得更精确的信号重建，同时仅取样（k，q）空间的2-4％，从而允许潜在的新的dMRI加速水平。

##### URL
[https://arxiv.org/abs/1707.09958](https://arxiv.org/abs/1707.09958)

##### PDF
[https://arxiv.org/pdf/1707.09958](https://arxiv.org/pdf/1707.09958)

