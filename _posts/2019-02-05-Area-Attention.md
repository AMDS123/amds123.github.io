---
layout: post
title: "Area Attention"
date: 2019-02-05 19:58:57
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption
author: Yang Li, Lukasz Kaiser, Samy Bengio, Si Si
mathjax: true
---

* content
{:toc}

##### Abstract
Existing attention mechanisms are trained to attend to individual items in a collection (the memory) with a predefined, fixed granularity, e.g., a word token or an image grid. We propose area attention: a way to attend to areas in the memory, where each area contains a group of items that are structurally adjacent, e.g., spatially for a 2D memory such as images, or temporally for a 1D memory such as natural language sentences. Importantly, the shape and the size of an area are dynamically determined via learning, which enables a model to attend to information with varying granularity. Area attention can easily work with existing model architectures such as multi-head attention for simultaneously attending to multiple areas in the memory. We evaluate area attention on two tasks: neural machine translation (both character and token-level) and image captioning, and improve upon strong (state-of-the-art) baselines in all the cases. These improvements are obtainable with a basic form of area attention that is parameter free.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10126](https://arxiv.org/abs/1810.10126)

##### PDF
[https://arxiv.org/pdf/1810.10126](https://arxiv.org/pdf/1810.10126)

