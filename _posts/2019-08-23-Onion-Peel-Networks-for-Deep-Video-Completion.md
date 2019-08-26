---
layout: post
title: "Onion-Peel Networks for Deep Video Completion"
date: 2019-08-23 08:51:41
categories: arXiv_CV
tags: arXiv_CV Attention
author: Seoung Wug Oh, Sungho Lee, Joon-Young Lee, Seon Joo Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the onion-peel networks for video completion. Given a set of reference images and a target image with holes, our network fills the hole by referring the contents in the reference images. Our onion-peel network progressively fills the hole from the hole boundary enabling it to exploit richer contextual information for the missing regions every step. Given a sufficient number of recurrences, even a large hole can be inpainted successfully. To attend to the missing information visible in the reference images, we propose an asymmetric attention block that computes similarities between the hole boundary pixels in the target and the non-hole pixels in the references in a non-local manner. With our attention block, our network can have an unlimited spatial-temporal window size and fill the holes with globally coherent contents. In addition, our framework is applicable to the image completion guided by the reference images without any modification, which is difficult to do with the previous methods. We validate that our method produces visually pleasing image and video inpainting results in realistic test cases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08718](http://arxiv.org/abs/1908.08718)

##### PDF
[http://arxiv.org/pdf/1908.08718](http://arxiv.org/pdf/1908.08718)

