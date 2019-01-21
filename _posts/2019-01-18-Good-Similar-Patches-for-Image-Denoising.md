---
layout: post
title: "Good Similar Patches for Image Denoising"
date: 2019-01-18 01:04:01
categories: arXiv_CV
tags: arXiv_CV
author: Si Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Patch-based denoising algorithms like BM3D have achieved outstanding performance. An important idea for the success of these methods is to exploit the recurrence of similar patches in an input image to estimate the underlying image structures. However, in these algorithms, the similar patches used for denoising are obtained via Nearest Neighbour Search (NNS) and are sometimes not optimal. First, due to the existence of noise, NNS can select similar patches with similar noise patterns to the reference patch. Second, the unreliable noisy pixels in digital images can bring a bias to the patch searching process and result in a loss of color fidelity in the final denoising result. We observe that given a set of good similar patches, their distribution is not necessarily centered at the noisy reference patch and can be approximated by a Gaussian component. Based on this observation, we present a patch searching method that clusters similar patch candidates into patch groups using Gaussian Mixture Model-based clustering, and selects the patch group that contains the reference patch as the final patches for denoising. We also use an unreliable pixel estimation algorithm to pre-process the input noisy images to further improve the patch searching. Our experiments show that our approach can better capture the underlying patch structures and can consistently enable the state-of-the-art patch-based denoising algorithms, such as BM3D, LPCA and PLOW, to better denoise images by providing them with patches found by our approach while without modifying these algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06046](http://arxiv.org/abs/1901.06046)

##### PDF
[http://arxiv.org/pdf/1901.06046](http://arxiv.org/pdf/1901.06046)

