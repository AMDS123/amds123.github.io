---
layout: post
title: "Training deep learning based image denoisers from undersampled measurements without ground truth and without image prior"
date: 2018-12-19 15:46:52
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Magauiya Zhussip, Shakarim Soltanayev, Se Young Chun
mathjax: true
---

* content
{:toc}

##### Abstract
Compressive sensing is a method to recover the original image from undersampled measurements. In order to overcome the ill-posedness of this inverse problem, image priors are used such as sparsity in the wavelet domain, minimum total-variation, or self-similarity. Recently, deep learning based compressive image recovery methods have been proposed and have yielded state-of-the-art performances. They used deep learning based data-driven approaches instead of hand-crafted image priors to solve the ill-posed inverse problem with undersampled data. Ironically, training deep neural networks for them requires "clean" ground truth images, but obtaining the best quality images from undersampled data requires well-trained deep neural networks. To resolve this dilemma, we propose novel methods based on two well-grounded theories: denoiser-approximate message passing and Stein's unbiased risk estimator. Our proposed methods were able to train deep learning based image denoisers from undersampled measurements without ground truth images and without image priors, and to recover images with state-of-the-art qualities from undersampled data. We evaluated our methods for various compressive sensing recovery problems with Gaussian random, coded diffraction pattern, and compressive sensing MRI measurement matrices. Our methods yielded state-of-the-art performances for all cases without ground truth images and without image priors. They also yielded comparable performances to the methods with ground truth data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.00961](http://arxiv.org/abs/1806.00961)

##### PDF
[http://arxiv.org/pdf/1806.00961](http://arxiv.org/pdf/1806.00961)

