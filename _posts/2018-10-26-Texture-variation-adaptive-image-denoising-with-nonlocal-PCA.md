---
layout: post
title: "Texture variation adaptive image denoising with nonlocal PCA"
date: 2018-10-26 11:53:39
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Wenzhao Zhao, Qiegen Liu, Yisong Lv, Binjie Qin
mathjax: true
---

* content
{:toc}

##### Abstract
Image textures, as a kind of local variations, provide important information for human visual system. Many image textures, especially the small-scale or stochastic textures are rich in high-frequency variations, and are difficult to be preserved. Current state-of-the-art denoising algorithms typically adopt a nonlocal approach consisting of image patch grouping and group-wise denoising filtering. To achieve a better image denoising while preserving the variations in texture, we first adaptively group high correlated image patches with the same kinds of texture elements (texels) via an adaptive clustering method. This adaptive clustering method is applied in an over-clustering-and-iterative-merging approach, where its noise robustness is improved with a custom merging threshold relating to the noise level and cluster size. For texture-preserving denoising of each cluster, considering that the variations in texture are captured and wrapped in not only the between-dimension energy variations but also the within-dimension variations of PCA transform coefficients, we further propose a PCA-transform-domain variation adaptive filtering method to preserve the local variations in textures. Experiments on natural images show the superiority of the proposed transform-domain variation adaptive filtering to traditional PCA-based hard or soft threshold filtering. As a whole, the proposed denoising method achieves a favorable texture preserving performance both quantitatively and visually, especially for stochastic textures, which is further verified in camera raw image denoising.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11282](http://arxiv.org/abs/1810.11282)

##### PDF
[http://arxiv.org/pdf/1810.11282](http://arxiv.org/pdf/1810.11282)

