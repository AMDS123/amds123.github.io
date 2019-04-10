---
layout: post
title: "Rain O'er Me: Synthesizing real rain to derain with data distillation"
date: 2019-04-09 11:38:24
categories: arXiv_CV
tags: arXiv_CV
author: Huangxing Lin, Yanlong Li, Xinghao Ding, Weihong Zeng, Yue Huang, John Paisley
mathjax: true
---

* content
{:toc}

##### Abstract
We present a supervised technique for learning to remove rain from images without using synthetic rain software. The method is based on a two-stage data distillation approach: 1) A rainy image is first paired with a coarsely derained version using on a simple filtering technique ("rain-to-clean"). 2) Then a clean image is randomly matched with the rainy soft-labeled pair. Through a shared deep neural network, the rain that is removed from the first image is then added to the clean image to generate a second pair ("clean-to-rain"). The neural network simultaneously learns to map both images such that high resolution structure in the clean images can inform the deraining of the rainy images. Demonstrations show that this approach can address those visual characteristics of rain not easily synthesized by software in the usual way.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04605](http://arxiv.org/abs/1904.04605)

##### PDF
[http://arxiv.org/pdf/1904.04605](http://arxiv.org/pdf/1904.04605)

