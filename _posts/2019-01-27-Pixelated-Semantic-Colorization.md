---
layout: post
title: "Pixelated Semantic Colorization"
date: 2019-01-27 20:28:48
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding CNN Semantic_Segmentation
author: Jiaojiao Zhao, Jungong Han, Ling Shao, Cees G. M. Snoek
mathjax: true
---

* content
{:toc}

##### Abstract
While many image colorization algorithms have recently shown the capability of producing plausible color versions from gray-scale photographs, they still suffer from limited semantic understanding. To address this shortcoming, we propose to exploit pixelated object semantics to guide image colorization. The rationale is that human beings perceive and distinguish colors based on the semantic categories of objects. Starting from an autoregressive model, we generate image color distributions, from which diverse colored results are sampled. We propose two ways to incorporate object semantics into the colorization model: through a pixelated semantic embedding and a pixelated semantic generator. Specifically, the proposed convolutional neural network includes two branches. One branch learns what the object is, while the other branch learns the object colors. The network jointly optimizes a color embedding loss, a semantic segmentation loss and a color generation loss, in an end-to-end fashion. Experiments on PASCAL VOC2012 and COCO-stuff reveal that our network, when trained with semantic segmentation labels, produces more realistic and finer results compared to the colorization state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10889](http://arxiv.org/abs/1901.10889)

##### PDF
[http://arxiv.org/pdf/1901.10889](http://arxiv.org/pdf/1901.10889)

