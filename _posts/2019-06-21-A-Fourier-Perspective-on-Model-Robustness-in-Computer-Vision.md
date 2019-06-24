---
layout: post
title: "A Fourier Perspective on Model Robustness in Computer Vision"
date: 2019-06-21 07:31:26
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Dong Yin, Raphael Gontijo Lopes, Jonathon Shlens, Ekin D. Cubuk, Justin Gilmer
mathjax: true
---

* content
{:toc}

##### Abstract
Achieving robustness to distributional shift is a longstanding and challenging goal of computer vision. Data augmentation is a commonly used approach for improving robustness, however robustness gains are typically not uniform across corruption types. Indeed increasing performance in the presence of random noise is often met with reduced performance on other corruptions such as contrast change. Understanding when and why these sorts of trade-offs occur is a crucial step towards mitigating them. Towards this end, we investigate recently observed trade-offs caused by Gaussian data augmentation and adversarial training. We find that both methods improve robustness to corruptions that are concentrated in the high frequency domain while reducing robustness to corruptions that are concentrated in the low frequency domain. This suggests that one way to mitigate these trade-offs via data augmentation is to use a more diverse set of augmentations. Towards this end we observe that AutoAugment, a recently proposed data augmentation policy optimized for clean accuracy, achieves state-of-the-art robustness on the CIFAR-10-C and ImageNet-C benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08988](http://arxiv.org/abs/1906.08988)

##### PDF
[http://arxiv.org/pdf/1906.08988](http://arxiv.org/pdf/1906.08988)

