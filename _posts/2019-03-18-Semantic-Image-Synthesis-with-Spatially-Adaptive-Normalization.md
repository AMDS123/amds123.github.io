---
layout: post
title: "Semantic Image Synthesis with Spatially-Adaptive Normalization"
date: 2019-03-18 08:12:23
categories: arXiv_AI
tags: arXiv_AI
author: Taesung Park, Ming-Yu Liu, Ting-Chun Wang, Jun-Yan Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose spatially-adaptive normalization, a simple but effective layer for synthesizing photorealistic images given an input semantic layout. Previous methods directly feed the semantic layout as input to the deep network, which is then processed through stacks of convolution, normalization, and nonlinearity layers. We show that this is suboptimal as the normalization layers tend to ``wash away'' semantic information. To address the issue, we propose using the input layout for modulating the activations in normalization layers through a spatially-adaptive, learned transformation. Experiments on several challenging datasets demonstrate the advantage of the proposed method over existing approaches, regarding both visual fidelity and alignment with input layouts. Finally, our model allows user control over both semantic and style as synthesizing images. Code will be available at https://github.com/NVlabs/SPADE .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07291](http://arxiv.org/abs/1903.07291)

##### PDF
[http://arxiv.org/pdf/1903.07291](http://arxiv.org/pdf/1903.07291)

