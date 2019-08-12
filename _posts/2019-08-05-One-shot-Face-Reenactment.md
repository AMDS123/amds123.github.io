---
layout: post
title: "One-shot Face Reenactment"
date: 2019-08-05 13:46:59
categories: arXiv_CV
tags: arXiv_CV Face
author: Yunxuan Zhang, Siwei Zhang, Yue He, Cheng Li, Chen Change Loy, Ziwei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
To enable realistic shape (e.g. pose and expression) transfer, existing face reenactment methods rely on a set of target faces for learning subject-specific traits. However, in real-world scenario end-users often only have one target face at hand, rendering existing methods inapplicable. In this work, we bridge this gap by proposing a novel one-shot face reenactment learning framework. Our key insight is that the one-shot learner should be able to disentangle and compose appearance and shape information for effective modeling. Specifically, the target face appearance and the source face shape are first projected into latent spaces with their corresponding encoders. Then these two latent spaces are associated by learning a shared decoder that aggregates multi-level features to produce the final reenactment results. To further improve the synthesizing quality on mustache and hair regions, we additionally propose FusionNet which combines the strengths of our learned decoder and the traditional warping method. Extensive experiments show that our one-shot face reenactment system achieves superior transfer fidelity as well as identity preserving capability than alternatives. More remarkably, our approach trained with only one target image per subject achieves competitive results to those using a set of target images, demonstrating the practical merit of this work. Code, models and an additional set of reenacted faces have been publicly released at the project page.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03251](https://arxiv.org/abs/1908.03251)

##### PDF
[https://arxiv.org/pdf/1908.03251](https://arxiv.org/pdf/1908.03251)

