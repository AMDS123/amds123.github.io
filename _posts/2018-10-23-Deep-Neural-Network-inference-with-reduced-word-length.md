---
layout: post
title: "Deep Neural Network inference with reduced word length"
date: 2018-10-23 13:48:53
categories: arXiv_AI
tags: arXiv_AI Inference Recognition
author: Lukas Mauch, Bin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNN) are powerful models for many pattern recognition tasks, yet their high computational complexity and memory requirement limit them to applications on high-performance computing platforms. In this paper, we propose a new method to evaluate DNNs trained with 32bit floating point (float32) accuracy using only low precision integer arithmetics in combination with binary shift and clipping operations. Because hardware implementation of these operations is much simpler than high precision floating point calculation, our method can be used for an efficient DNN inference on dedicated hardware. In experiments on MNIST, we demonstrate that DNNs trained with float32 can be evaluated using a combination of 2bit integer arithmetics and a few float32 calculations in each layer or only 3bit integer arithmetics in combination with binary shift and clipping without significant performance degradation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09854](http://arxiv.org/abs/1810.09854)

##### PDF
[http://arxiv.org/pdf/1810.09854](http://arxiv.org/pdf/1810.09854)

