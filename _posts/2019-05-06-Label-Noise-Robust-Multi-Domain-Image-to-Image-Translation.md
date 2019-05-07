---
layout: post
title: "Label-Noise Robust Multi-Domain Image-to-Image Translation"
date: 2019-05-06 17:57:43
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Takuhiro Kaneko, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-domain image-to-image translation is a problem where the goal is to learn mappings among multiple domains. This problem is challenging in terms of scalability because it requires the learning of numerous mappings, the number of which increases proportional to the number of domains. However, generative adversarial networks (GANs) have emerged recently as a powerful framework for this problem. In particular, label-conditional extensions (e.g., StarGAN) have become a promising solution owing to their ability to address this problem using only a single unified model. Nonetheless, a limitation is that they rely on the availability of large-scale clean-labeled data, which are often laborious or impractical to collect in a real-world scenario. To overcome this limitation, we propose a novel model called the label-noise robust image-to-image translation model (RMIT) that can learn a clean label conditional generator even when noisy labeled data are only available. In particular, we propose a novel loss called the virtual cycle consistency loss that is able to regularize cyclic reconstruction independently of noisy labeled data, as well as we introduce advanced techniques to boost the performance in practice. Our experimental results demonstrate that RMIT is useful for obtaining label-noise robustness in various settings including synthetic and real-world noise.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02185](http://arxiv.org/abs/1905.02185)

##### PDF
[http://arxiv.org/pdf/1905.02185](http://arxiv.org/pdf/1905.02185)

