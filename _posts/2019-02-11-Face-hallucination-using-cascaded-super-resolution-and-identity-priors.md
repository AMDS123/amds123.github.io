---
layout: post
title: "Face hallucination using cascaded super-resolution and identity priors"
date: 2019-02-11 07:59:44
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Face CNN Recognition Face_Recognition
author: Klemen Grm, Simon Dobri&#x161;ek, Walter J. Scheirer, Vitomir &#x160;truc
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we address the problem of hallucinating high-resolution facial images from unaligned low-resolution inputs at high magnification factors. We approach the problem with convolutional neural networks (CNNs) and propose a novel (deep) face hallucination model that incorporates identity priors into the learning procedure. The model consists of two main parts: i) a cascaded super-resolution network that upscales the low-resolution images, and ii) an ensemble of face recognition models that act as identity priors for the super-resolution network during training. Different from competing super-resolution approaches that typically rely on a single model for upscaling (even with large magnification factors), our network uses a cascade of multiple SR models that progressively upscale the low-resolution images using steps of $2\times$. This characteristic allows us to apply supervision signals (target appearances) at different resolutions and incorporate identity constraints at multiple-scales. Our model is able to upscale (very) low-resolution images captured in unconstrained conditions and produce visually convincing results. We rigorously evaluate the proposed model on a large datasets of facial images and report superior performance compared to the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10938](http://arxiv.org/abs/1805.10938)

##### PDF
[http://arxiv.org/pdf/1805.10938](http://arxiv.org/pdf/1805.10938)

