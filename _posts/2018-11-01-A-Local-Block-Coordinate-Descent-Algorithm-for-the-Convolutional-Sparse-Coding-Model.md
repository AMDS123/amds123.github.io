---
layout: post
title: "A Local Block Coordinate Descent Algorithm for the Convolutional Sparse Coding Model"
date: 2018-11-01 11:02:38
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Gradient_Descent
author: Ev Zisselman, Jeremias Sulam, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
The Convolutional Sparse Coding (CSC) model has recently gained considerable traction in the signal and image processing communities. By providing a global, yet tractable, model that operates on the whole image, the CSC was shown to overcome several limitations of the patch-based sparse model while achieving superior performance in various applications. Contemporary methods for pursuit and learning the CSC dictionary often rely on the Alternating Direction Method of Multipliers (ADMM) in the Fourier domain for the computational convenience of convolutions, while ignoring the local characterizations of the image. A recent work by Papyan et al. suggested the SBDL algorithm for the CSC, while operating locally on image patches. SBDL demonstrates better performance compared to the Fourier-based methods, albeit still relying on the ADMM. In this work we maintain the localized strategy of the SBDL, while proposing a new and much simpler approach based on the Block Coordinate Descent algorithm - this method is termed Local Block Coordinate Descent (LoBCoD). Furthermore, we introduce a novel stochastic gradient descent version of LoBCoD for training the convolutional filters. The Stochastic-LoBCoD leverages the benefits of online learning, while being applicable to a single training image. We demonstrate the advantages of the proposed algorithms for image inpainting and multi-focus image fusion, achieving state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00312](http://arxiv.org/abs/1811.00312)

##### PDF
[http://arxiv.org/pdf/1811.00312](http://arxiv.org/pdf/1811.00312)

