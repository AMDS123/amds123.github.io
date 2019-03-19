---
layout: post
title: "Counterpoint by Convolution"
date: 2019-03-18 02:04:23
categories: arXiv_SD
tags: arXiv_SD CNN
author: Cheng-Zhi Anna Huang, Tim Cooijmans, Adam Roberts, Aaron Courville, Douglas Eck
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning models of music typically break up the task of composition into a chronological process, composing a piece of music in a single pass from beginning to end. On the contrary, human composers write music in a nonlinear fashion, scribbling motifs here and there, often revisiting choices previously made. In order to better approximate this process, we train a convolutional neural network to complete partial musical scores, and explore the use of blocked Gibbs sampling as an analogue to rewriting. Neither the model nor the generative procedure are tied to a particular causal direction of composition. Our model is an instance of orderless NADE (Uria et al., 2014), which allows more direct ancestral sampling. However, we find that Gibbs sampling greatly improves sample quality, which we demonstrate to be due to some conditional distributions being poorly modeled. Moreover, we show that even the cheap approximate blocked Gibbs procedure from Yao et al. (2014) yields better samples than ancestral sampling, based on both log-likelihood and human evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07227](http://arxiv.org/abs/1903.07227)

##### PDF
[http://arxiv.org/pdf/1903.07227](http://arxiv.org/pdf/1903.07227)

