---
layout: post
title: "Spatiotemporal Pyramid Network for Video Action Recognition"
date: 2019-03-04 01:36:41
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Relation Recognition
author: Yunbo Wang, Mingsheng Long, Jianmin Wang, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Two-stream convolutional networks have shown strong performance in video action recognition tasks. The key idea is to learn spatiotemporal features by fusing convolutional networks spatially and temporally. However, it remains unclear how to model the correlations between the spatial and temporal structures at multiple abstraction levels. First, the spatial stream tends to fail if two videos share similar backgrounds. Second, the temporal stream may be fooled if two actions resemble in short snippets, though appear to be distinct in the long term. We propose a novel spatiotemporal pyramid network to fuse the spatial and temporal features in a pyramid structure such that they can reinforce each other. From the architecture perspective, our network constitutes hierarchical fusion strategies which can be trained as a whole using a unified spatiotemporal loss. A series of ablation experiments support the importance of each fusion strategy. From the technical perspective, we introduce the spatiotemporal compact bilinear operator into video analysis tasks. This operator enables efficient training of bilinear fusion operations which can capture full interactions between the spatial and temporal features. Our final network achieves state-of-the-art results on standard video datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01038](http://arxiv.org/abs/1903.01038)

##### PDF
[http://arxiv.org/pdf/1903.01038](http://arxiv.org/pdf/1903.01038)

