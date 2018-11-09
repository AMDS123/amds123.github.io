---
layout: post
title: "Blockwise Parallel Decoding for Deep Autoregressive Models"
date: 2018-11-07 19:09:40
categories: arXiv_CL
tags: arXiv_CL Super_Resolution Attention CNN Prediction
author: Mitchell Stern, Noam Shazeer, Jakob Uszkoreit
mathjax: true
---

* content
{:toc}

##### Abstract
Deep autoregressive sequence-to-sequence models have demonstrated impressive performance across a wide variety of tasks in recent years. While common architecture classes such as recurrent, convolutional, and self-attention networks make different trade-offs between the amount of computation needed per layer and the length of the critical path at training time, generation still remains an inherently sequential process. To overcome this limitation, we propose a novel blockwise parallel decoding scheme in which we make predictions for multiple time steps in parallel then back off to the longest prefix validated by a scoring model. This allows for substantial theoretical improvements in generation speed when applied to architectures that can process output sequences in parallel. We verify our approach empirically through a series of experiments using state-of-the-art self-attention models for machine translation and image super-resolution, achieving iteration reductions of up to 2x over a baseline greedy decoder with no loss in quality, or up to 7x in exchange for a slight decrease in performance. In terms of wall-clock time, our fastest models exhibit real-time speedups of up to 4x over standard greedy decoding.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03115](http://arxiv.org/abs/1811.03115)

##### PDF
[http://arxiv.org/pdf/1811.03115](http://arxiv.org/pdf/1811.03115)

