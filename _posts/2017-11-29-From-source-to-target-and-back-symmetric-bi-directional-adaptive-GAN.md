---
layout: post
title: "From source to target and back: symmetric bi-directional adaptive GAN"
date: 2017-11-29 10:14:52
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Paolo Russo, Fabio Maria Carlucci, Tatiana Tommasi, Barbara Caputo
mathjax: true
---

* content
{:toc}

##### Abstract
The effectiveness of generative adversarial approaches in producing images according to a specific style or visual domain has recently opened new directions to solve the unsupervised domain adaptation problem. It has been shown that source labeled images can be modified to mimic target samples making it possible to train directly a classifier in the target domain, despite the original lack of annotated data. Inverse mappings from the target to the source domain have also been evaluated but only passing through adapted feature spaces, thus without new image generation. In this paper we propose to better exploit the potential of generative adversarial networks for adaptation by introducing a novel symmetric mapping among domains. We jointly optimize bi-directional image transformations combining them with target self-labeling. Moreover we define a new class consistency loss that aligns the generators in the two directions imposing to conserve the class identity of an image passing through both domain mappings. A detailed qualitative and quantitative analysis of the reconstructed images confirm the power of our approach. By integrating the two domain specific classifiers obtained with our bi-directional network we exceed previous state-of-the-art unsupervised adaptation results on four different benchmark datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.08824](https://arxiv.org/abs/1705.08824)

##### PDF
[https://arxiv.org/pdf/1705.08824](https://arxiv.org/pdf/1705.08824)

