---
layout: post
title: "WaveGlow: A Flow-based Generative Network for Speech Synthesis"
date: 2018-10-31 03:22:25
categories: arXiv_AI
tags: arXiv_AI
author: Ryan Prenger, Rafael Valle, Bryan Catanzaro
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose WaveGlow: a flow-based network capable of generating high quality speech from mel-spectrograms. WaveGlow combines insights from Glow and WaveNet in order to provide fast, efficient and high-quality audio synthesis, without the need for auto-regression. WaveGlow is implemented using only a single network, trained using only a single cost function: maximizing the likelihood of the training data, which makes the training procedure simple and stable. Our PyTorch implementation produces audio samples at a rate of more than 500 kHz on an NVIDIA V100 GPU. Mean Opinion Scores show that it delivers audio quality as good as the best publicly available WaveNet implementation. All code will be made publicly available online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00002](http://arxiv.org/abs/1811.00002)

##### PDF
[http://arxiv.org/pdf/1811.00002](http://arxiv.org/pdf/1811.00002)

