---
layout: post
title: "Area Attention"
date: 2018-10-23 23:14:27
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption
author: Yang Li, Lukasz Kaiser, Samy Bengio, Si Si
mathjax: true
---

* content
{:toc}

##### Abstract
Existing attention mechanisms, are mostly item-based in that a model is designed to attend to a single item in a collection of items (the memory). Intuitively, an area in the memory that may contain multiple items can be worth attending to as a whole. We propose area attention: a way to attend to an area of the memory, where each area contains a group of items that are either spatially adjacent when the memory has a 2-dimensional structure, such as images, or temporally adjacent for 1-dimensional memory, such as natural language sentences. Importantly, the size of an area, i.e., the number of items in an area, can vary depending on the learned coherence of the adjacent items. By giving the model the option to attend to an area of items, instead of only a single item, we hope attention mechanisms can better capture the nature of the task. Area attention can work along multi-head attention for attending to multiple areas in the memory. We evaluate area attention on two tasks: neural machine translation and image captioning, and improve upon strong (state-of-the-art) baselines in both cases. These improvements are obtainable with a basic form of area attention that is parameter free. In addition to proposing the novel concept of area attention, we contribute an efficient way for computing it by leveraging the technique of summed area tables.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10126](https://arxiv.org/abs/1810.10126)

##### PDF
[https://arxiv.org/pdf/1810.10126](https://arxiv.org/pdf/1810.10126)

