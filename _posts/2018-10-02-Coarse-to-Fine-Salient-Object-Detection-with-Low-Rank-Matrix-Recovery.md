---
layout: post
title: "Coarse-to-Fine Salient Object Detection with Low-Rank Matrix Recovery"
date: 2018-10-02 05:39:33
categories: arXiv_CV
tags: arXiv_CV Regularization Salient Object_Detection Sparse Detection Relation
author: Qi Zheng, Shujian Yu, Xinge You, Qinmu Peng, Wei Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Low-Rank Matrix Recovery (LRMR) has recently been applied to saliency detection by decomposing image features into a low-rank component associated with background and a sparse component associated with visual salient regions. Despite its great potential, existing LRMR-based saliency detection methods seldom consider the inter-relationship among elements within these two components, thus are prone to generating scattered or incomplete saliency maps. In this paper, we introduce a novel and efficient LRMR-based saliency detection model under a coarse-to-fine framework to circumvent this limitation. First, we roughly measure the saliency of image regions with a baseline LRMR model that integrates a $\ell_1$-norm sparsity constraint and a Laplacian regularization smooth term. Given samples from the coarse saliency map, we then learn a projection that maps image features to refined saliency values, to significantly sharpen the object boundaries and to preserve the object entirety. We evaluate our framework against existing LRMR based methods on three benchmark datasets. Experimental results validate the superiority of our method as well as the effectiveness of our suggested coarse-to-fine framework, especially for images containing multiple objects.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.07936](https://arxiv.org/abs/1805.07936)

##### PDF
[https://arxiv.org/pdf/1805.07936](https://arxiv.org/pdf/1805.07936)

