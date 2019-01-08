---
layout: post
title: "Double Weighted Truncated Nuclear Norm Regularization for Low-Rank Matrix Completion"
date: 2019-01-07 09:04:37
categories: arXiv_CV
tags: arXiv_CV Regularization Attention Optimization Gradient_Descent
author: Shengke Xue, Wenyuan Qiu, Fan Liu, Xinyu Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Matrix completion focuses on recovering a matrix from a small subset of its observed elements, and has already gained cumulative attention in computer vision. Many previous approaches formulate this issue as a low-rank matrix approximation problem. Recently, a truncated nuclear norm has been presented as a surrogate of traditional nuclear norm, for better estimation to the rank of a matrix. The truncated nuclear norm regularization (TNNR) method is applicable in real-world scenarios. However, it is sensitive to the selection of the number of truncated singular values and requires numerous iterations to converge. Hereby, this paper proposes a revised approach called the double weighted truncated nuclear norm regularization (DW-TNNR), which assigns different weights to the rows and columns of a matrix separately, to accelerate the convergence with acceptable performance. The DW-TNNR is more robust to the number of truncated singular values than the TNNR. Instead of the iterative updating scheme in the second step of TNNR, this paper devises an efficient strategy that uses a gradient descent manner in a concise form, with a theoretical guarantee in optimization. Sufficient experiments conducted on real visual data prove that DW-TNNR has promising performance and holds the superiority in both speed and accuracy for matrix completion.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01711](http://arxiv.org/abs/1901.01711)

##### PDF
[http://arxiv.org/pdf/1901.01711](http://arxiv.org/pdf/1901.01711)

