---
layout: post
title: "Backprop with Approximate Activations for Memory-efficient Network Training"
date: 2019-01-23 16:40:09
categories: arXiv_CV
tags: arXiv_CV
author: Ayan Chakrabarti, Benjamin Moseley
mathjax: true
---

* content
{:toc}

##### Abstract
Larger and deeper neural network architectures deliver improved accuracy on a variety of tasks, but also require a large amount of memory for training to store intermediate activations for back-propagation. We introduce an approximation strategy to significantly reduce this memory footprint, with minimal effect on training performance and negligible computational cost. Our method replaces intermediate activations with lower-precision approximations to free up memory, after the full-precision versions have been used for computation in subsequent layers in the forward pass. Only these approximate activations are retained for use in the backward pass. Compared to naive low-precision computation, our approach limits the accumulation of errors across layers and allows the use of much lower-precision approximations without affecting training accuracy. Experiments on CIFAR and ImageNet show that our method yields performance comparable to full-precision training, while storing activations at a fraction of the memory cost with 8- and even 4-bit fixed-point precision.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.07988](https://arxiv.org/abs/1901.07988)

##### PDF
[https://arxiv.org/pdf/1901.07988](https://arxiv.org/pdf/1901.07988)

