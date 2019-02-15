---
layout: post
title: "Motion Compensated Dynamic MRI Reconstruction with Local Affine Optical Flow Estimation"
date: 2019-02-14 00:00:52
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding Optimization
author: Ningning Zhao, Daniel O&#x27;Connor, Adrian Basarab, Dan Ruan, Peng Hu, Ke Sheng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel framework to reconstruct the dynamic magnetic resonance images (DMRI) with motion compensation (MC). Due to the inherent motion effects during DMRI acquisition, reconstruction of DMRI using motion estimation/compensation (ME/MC) has been studied under a compressed sensing (CS) scheme. In this paper, by embedding the intensity-based optical flow (OF) constraint into the traditional CS scheme, we are able to couple the DMRI reconstruction with motion field estimation. The formulated optimization problem is solved by a primal-dual algorithm with linesearch due to its efficiency when dealing with non-differentiable problems. With the estimated motion field, the DMRI reconstruction is refined through MC. By employing the multi-scale coarse-to-fine strategy, we are able to update the variables(temporal image sequences and motion vectors) and to refine the image reconstruction alternately. Moreover, the proposed framework is capable of handling a wide class of prior information (regularizations) for DMRI reconstruction, such as sparsity, low rank and total variation. Experiments on various DMRI data, ranging from in vivo lung to cardiac dataset, validate the reconstruction quality improvement using the proposed scheme in comparison to several state-of-the-art algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1707.07089](http://arxiv.org/abs/1707.07089)

##### PDF
[http://arxiv.org/pdf/1707.07089](http://arxiv.org/pdf/1707.07089)

