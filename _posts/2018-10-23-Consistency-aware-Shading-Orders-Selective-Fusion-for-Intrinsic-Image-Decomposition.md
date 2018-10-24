---
layout: post
title: "Consistency-aware Shading Orders Selective Fusion for Intrinsic Image Decomposition"
date: 2018-10-23 07:53:30
categories: arXiv_CV
tags: arXiv_CV Face
author: Yuanliu Liu, Ang Li, Zejian Yuan, Badong Chen, Nanning Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of decomposing a single image into reflectance and shading. The difficulty comes from the fact that the components of image---the surface albedo, the direct illumination, and the ambient illumination---are coupled heavily in observed image. We propose to infer the shading by ordering pixels by their relative brightness, without knowing the absolute values of the image components beforehand. The pairwise shading orders are estimated in two ways: brightness order and low-order fittings of local shading field. The brightness order is a non-local measure, which can be applied to any pair of pixels including those whose reflectance and shading are both different. The low-order fittings are used for pixel pairs within local regions of smooth shading. Together, they can capture both global order structure and local variations of the shading. We propose a Consistency-aware Selective Fusion (CSF) to integrate the pairwise orders into a globally consistent order. The iterative selection process solves the conflicts between the pairwise orders obtained by different estimation methods. Inconsistent or unreliable pairwise orders will be automatically excluded from the fusion to avoid polluting the global order. Experiments on the MIT Intrinsic Image dataset show that the proposed model is effective at recovering the shading including deep shadows. Our model also works well on natural images from the IIW dataset, the UIUC Shadow dataset and the NYU-Depth dataset, where the colors of direct lights and ambient lights are quite different.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09706](http://arxiv.org/abs/1810.09706)

##### PDF
[http://arxiv.org/pdf/1810.09706](http://arxiv.org/pdf/1810.09706)

