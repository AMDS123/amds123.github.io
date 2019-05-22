---
layout: post
title: "Mesh-based Camera Pairs Selection and Occlusion-Aware Masking for Mesh Refinement"
date: 2019-05-21 08:51:15
categories: arXiv_CV
tags: arXiv_CV Sparse Face Quantitative
author: Andrea Romanoni, Matteo Matteucci
mathjax: true
---

* content
{:toc}

##### Abstract
Many Multi-View-Stereo algorithms extract a 3D mesh model of a scene, after fusing depth maps into a volumetric representation of the space. Due to the limited scalability of such representations, the estimated model does not capture fine details of the scene. Therefore a mesh refinement algorithm is usually applied; it improves the mesh resolution and accuracy by minimizing the photometric error induced by the 3D model into pairs of cameras. The choice of these pairs significantly affects the quality of the refinement and usually relies on sparse 3D points belonging to the surface. Instead, in this paper, to increase the quality of pairs selection, we exploit the 3D model (before the refinement) to compute five metrics: scene coverage, mutual image overlap, image resolution, camera parallax, and a new symmetry term. To improve the refinement robustness, we also propose an explicit method to manage occlusions, which may negatively affect the computation of the photometric error. The proposed method takes into account the depth of the model while computing the similarity measure and its gradient. We quantitatively and qualitatively validated our approach on publicly available datasets against state of the art reconstruction methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08502](http://arxiv.org/abs/1905.08502)

##### PDF
[http://arxiv.org/pdf/1905.08502](http://arxiv.org/pdf/1905.08502)

