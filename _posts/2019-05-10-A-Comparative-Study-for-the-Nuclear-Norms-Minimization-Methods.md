---
layout: post
title: "A Comparative Study for the Nuclear Norms Minimization Methods"
date: 2019-05-10 08:58:01
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Zhiyuan Zha, Bihan Wen, Jiachao Zhang, Jiantao Zhou, Ce Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
The nuclear norm minimization (NNM) is commonly used to approximate the matrix rank by shrinking all singular values equally. However, the singular values have clear physical meanings in many practical problems, and NNM may not be able to faithfully approximate the matrix rank. To alleviate the above-mentioned limitation of NNM, recent studies have suggested that the weighted nuclear norm minimization (WNNM) can achieve a better rank estimation than NNM, which heuristically set the weight being inverse to the singular values. However, it still lacks a rigorous explanation why WNNM is more effective than NMM in various applications. In this paper, we analyze NNM and WNNM from the perspective of group sparse representation (GSR). Concretely, an adaptive dictionary learning method is devised to connect the rank minimization and GSR models. Based on the proposed dictionary, we prove that NNM and WNNM are equivalent to L1-norm minimization and the weighted L1-norm minimization in GSR, respectively. Inspired by enhancing sparsity of the weighted L1-norm minimization in comparison with L1-norm minimization in sparse representation, we thus explain that WNNM is more effective than NMM. By integrating the image nonlocal self-similarity (NSS) prior with the WNNM model, we then apply it to solve the image denoising problem. Experimental results demonstrate that WNNM is more effective than NNM and outperforms several state-of-the-art methods in both objective and perceptual quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1608.04517](http://arxiv.org/abs/1608.04517)

##### PDF
[http://arxiv.org/pdf/1608.04517](http://arxiv.org/pdf/1608.04517)

