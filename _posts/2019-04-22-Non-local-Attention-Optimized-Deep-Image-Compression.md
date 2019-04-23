---
layout: post
title: "Non-local Attention Optimized Deep Image Compression"
date: 2019-04-22 07:51:17
categories: arXiv_CV
tags: arXiv_CV Attention Relation
author: Haojie Liu, Tong Chen, Peiyao Guo, Qiu Shen, Xun Cao, Yao Wang, Zhan Ma
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel Non-Local Attention Optimized Deep Image Compression (NLAIC) framework, which is built on top of the popular variational auto-encoder (VAE) structure. Our NLAIC framework embeds non-local operations in the encoders and decoders for both image and latent feature probability information (known as hyperprior) to capture both local and global correlations, and apply attention mechanism to generate masks that are used to weigh the features for the image and hyperprior, which implicitly adapt bit allocation for different features based on their importance. Furthermore, both hyperpriors and spatial-channel neighbors of the latent features are used to improve entropy coding. The proposed model outperforms the existing methods on Kodak dataset, including learned (e.g., Balle2019, Balle2018) and conventional (e.g., BPG, JPEG2000, JPEG) image compression methods, for both PSNR and MS-SSIM distortion metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09757](http://arxiv.org/abs/1904.09757)

##### PDF
[http://arxiv.org/pdf/1904.09757](http://arxiv.org/pdf/1904.09757)

