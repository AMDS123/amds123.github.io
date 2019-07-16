---
layout: post
title: "Recovery Guarantees for Compressible Signals with Adversarial Noise"
date: 2019-07-15 16:15:12
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial Sparse
author: Jasjeet Dhaliwal, Kyle Hambrook
mathjax: true
---

* content
{:toc}

##### Abstract
We provide recovery guarantees for compressible signals that have been corrupted with noise and extend the framework introduced in [1] to defend neural networks against $\ell_0$-norm and $\ell_2$-norm attacks. Concretely, for a signal that is approximately sparse in some transform domain and has been perturbed with noise, we provide guarantees for accurately recovering the signal in the transform domain. We can then use the recovered signal to reconstruct the signal in its original domain while largely removing the noise. Our results are general as they can be directly applied to most unitary transforms used in practice and hold for both $\ell_0$-norm bounded noise and $\ell_2$-norm bounded noise. In the case of $\ell_0$-norm bounded noise, we prove recovery guarantees for Iterative Hard Thresholding (IHT) and Basis Pursuit (BP). For the case of $\ell_2$-norm bounded noise, we provide recovery guarantees for BP. These guarantees theoretically bolster the defense framework introduced in [1] for defending neural networks against adversarial inputs. Finally, we experimentally demonstrate this defense framework using both IHT and BP against the One Pixel Attack [21], Carlini-Wagner $\ell_0$ and $\ell_2$ attacks [3], Jacobian Saliency Based attack [18], and the DeepFool attack [17] on CIFAR-10 [12], MNIST [13], and Fashion-MNIST [27] datasets. This expands beyond the experimental demonstrations of [1].

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06565](http://arxiv.org/abs/1907.06565)

##### PDF
[http://arxiv.org/pdf/1907.06565](http://arxiv.org/pdf/1907.06565)

