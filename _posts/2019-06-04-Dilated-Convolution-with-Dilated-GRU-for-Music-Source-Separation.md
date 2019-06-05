---
layout: post
title: "Dilated Convolution with Dilated GRU for Music Source Separation"
date: 2019-06-04 05:39:43
categories: arXiv_SD
tags: arXiv_SD Prediction
author: Jen-Yu Liu, Yi-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Stacked dilated convolutions used in Wavenet have been shown effective for generating high-quality audios. By replacing pooling/striding with dilation in convolution layers, they can preserve high-resolution information and still reach distant locations. Producing high-resolution predictions is also crucial in music source separation, whose goal is to separate different sound sources while maintaining the quality of the separated sounds. Therefore, this paper investigates using stacked dilated convolutions as the backbone for music source separation. However, while stacked dilated convolutions can reach wider context than standard convolutions, their effective receptive fields are still fixed and may not be wide enough for complex music audio signals. To reach information at remote locations, we propose to combine dilated convolution with a modified version of gated recurrent units (GRU) called the `Dilated GRU' to form a block. A Dilated GRU unit receives information from k steps before instead of the previous step for a fixed k. This modification allows a GRU unit to reach a location with fewer recurrent steps and run faster because it can execute partially in parallel. We show that the proposed model with a stack of such blocks performs equally well or better than the state-of-the-art models for separating vocals and accompaniments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01203](http://arxiv.org/abs/1906.01203)

##### PDF
[http://arxiv.org/pdf/1906.01203](http://arxiv.org/pdf/1906.01203)

