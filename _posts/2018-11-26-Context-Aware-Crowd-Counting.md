---
layout: post
title: "Context-Aware Crowd Counting"
date: 2018-11-26 15:31:22
categories: arXiv_CV
tags: arXiv_CV
author: Weizhe Liu, Mathieu Salzmann, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods for counting people in crowded scenes rely on deep networks to estimate crowd density. They typically use the same filters over the whole image or over large image patches. Only then do they estimate local scale to compensate for perspective distortion. This is typically achieved by training an auxiliary classifier to select, for predefined image patches, the best kernel size among a limited set of choices. As such, these methods are not end-to-end trainable and restricted in the scope of context they can leverage. In this paper, we introduce an end-to-end trainable deep architecture that combines features obtained using multiple receptive field sizes and learns the importance of each such feature at each image location. In other words, our approach adaptively encodes the scale of the contextual information required to accurately predict crowd density. This yields an algorithm that outperforms state-of-the-art crowd counting methods, especially when perspective effects are strong.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10452](https://arxiv.org/abs/1811.10452)

##### PDF
[https://arxiv.org/pdf/1811.10452](https://arxiv.org/pdf/1811.10452)

