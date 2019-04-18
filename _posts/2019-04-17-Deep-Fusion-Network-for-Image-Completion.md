---
layout: post
title: "Deep Fusion Network for Image Completion"
date: 2019-04-17 02:48:02
categories: arXiv_CV
tags: arXiv_CV Attention Quantitative
author: Xin Hong, Pengfei Xiong, Renhe Ji, Haoqiang Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep image completion usually fails to harmonically blend the restored image into existing content, especially in the boundary area. This paper handles with this problem from a new perspective of creating a smooth transition and proposes a concise Deep Fusion Network (DFNet). Firstly, a fusion block is introduced to generate a flexible alpha composition map for combining known and unknown regions. The fusion block not only provides a smooth fusion between restored and existing content, but also provides an attention map to make network focus more on the unknown pixels. In this way, it builds a bridge for structural and texture information, so that information can be naturally propagated from known region into completion. Furthermore, fusion blocks are embedded into several decoder layers of the network. Accompanied by the adjustable loss constraints on each layer, more accurate structure information are achieved. We qualitatively and quantitatively compare our method with other state-of-the-art methods on Places2 and CelebA datasets. The results show the superior performance of DFNet, especially in the aspects of harmonious texture transition, texture detail and semantic structural consistency. Our source code will be avaiable at: \url{https://github.com/hughplay/DFNet}

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08060](http://arxiv.org/abs/1904.08060)

##### PDF
[http://arxiv.org/pdf/1904.08060](http://arxiv.org/pdf/1904.08060)

