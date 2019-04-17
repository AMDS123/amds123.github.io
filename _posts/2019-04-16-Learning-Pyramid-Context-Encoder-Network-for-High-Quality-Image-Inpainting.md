---
layout: post
title: "Learning Pyramid-Context Encoder Network for High-Quality Image Inpainting"
date: 2019-04-16 05:51:37
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention
author: Yanhong Zeng, Jianlong Fu, Hongyang Chao, Baining Guo
mathjax: true
---

* content
{:toc}

##### Abstract
High-quality image inpainting requires filling missing regions in a damaged image with plausible content. Existing works either fill the regions by copying image patches or generating semantically-coherent patches from region context, while neglect the fact that both visual and semantic plausibility are highly-demanded. In this paper, we propose a Pyramid-context ENcoder Network (PEN-Net) for image inpainting by deep generative models. The PEN-Net is built upon a U-Net structure, which can restore an image by encoding contextual semantics from full resolution input, and decoding the learned semantic features back into images. Specifically, we propose a pyramid-context encoder, which progressively learns region affinity by attention from a high-level semantic feature map and transfers the learned attention to the previous low-level feature map. As the missing content can be filled by attention transfer from deep to shallow in a pyramid fashion, both visual and semantic coherence for image inpainting can be ensured. We further propose a multi-scale decoder with deeply-supervised pyramid losses and an adversarial loss. Such a design not only results in fast convergence in training, but more realistic results in testing. Extensive experiments on various datasets show the superior performance of the proposed network

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07475](http://arxiv.org/abs/1904.07475)

##### PDF
[http://arxiv.org/pdf/1904.07475](http://arxiv.org/pdf/1904.07475)

