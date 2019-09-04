---
layout: post
title: "MRI Reconstruction Using Deep Bayesian Inference"
date: 2019-09-03 12:54:58
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning
author: GuanXiong Luo, Na Zhao, Wenhao Jiang, Peng Cao
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: To develop a deep learning-based Bayesian inference for MRI reconstruction. Methods: We modeled the MRI reconstruction problem with Bayes's theorem, following the recently proposed PixelCNN++ method. The image reconstruction from incomplete k-space measurement was obtained by maximizing the posterior possibility. A generative network was utilized as the image prior, which was computationally tractable, and the k-space data fidelity was enforced by using an equality constraint. The stochastic backpropagation was utilized to calculate the descent gradient in the process of maximum a posterior, and a projected subgradient method was used to impose the equality constraint. In contrast to the other deep learning reconstruction methods, the proposed one used the likelihood of prior as the training loss and the objective function in reconstruction to improve the image quality. Results: The proposed method showed an improved performance in preserving image details and reducing aliasing artifacts, compared with GRAPPA, $\ell_1$-ESPRiT, and MODL, a state-of-the-art deep learning reconstruction method. The proposed method generally achieved more than 5 dB peak signal-to-noise ratio improvement for compressed sensing and parallel imaging reconstructions compared with the other methods. Conclusion: The Bayesian inference significantly improved the reconstruction performance, compared with the conventional $\ell_1$-sparsity prior in compressed sensing reconstruction tasks. More importantly, the proposed reconstruction framework can be generalized for most MRI reconstruction scenarios.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01127](https://arxiv.org/abs/1909.01127)

##### PDF
[https://arxiv.org/pdf/1909.01127](https://arxiv.org/pdf/1909.01127)

