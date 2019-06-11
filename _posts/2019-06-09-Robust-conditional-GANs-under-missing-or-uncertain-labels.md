---
layout: post
title: "Robust conditional GANs under missing or uncertain labels"
date: 2019-06-09 06:37:06
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Kiran Koshy Thekumparampil, Sewoong Oh, Ashish Khetan
mathjax: true
---

* content
{:toc}

##### Abstract
Matching the performance of conditional Generative Adversarial Networks with little supervision is an important task, especially in venturing into new domains. We design a new training algorithm, which is robust to missing or ambiguous labels. The main idea is to intentionally corrupt the labels of generated examples to match the statistics of the real data, and have a discriminator process the real and generated examples with corrupted labels. We showcase the robustness of this proposed approach both theoretically and empirically. We show that minimizing the proposed loss is equivalent to minimizing true divergence between real and generated data up to a multiplicative factor, and characterize this multiplicative factor as a function of the statistics of the uncertain labels. Experiments on MNIST dataset demonstrates that proposed architecture is able to achieve high accuracy in generating examples faithful to the class even with only a few examples per class.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.03579](https://arxiv.org/abs/1906.03579)

##### PDF
[https://arxiv.org/pdf/1906.03579](https://arxiv.org/pdf/1906.03579)

