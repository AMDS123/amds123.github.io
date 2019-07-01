---
layout: post
title: "A Novel Document Generation Process for Topic Detection based on Hierarchical Latent Tree Models"
date: 2019-06-28 03:15:45
categories: arXiv_CL
tags: arXiv_CL Detection
author: Peixian Chen, Zhourong Chen, Nevin L. Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel document generation process based on hierarchical latent tree models (HLTMs) learned from data. An HLTM has a layer of observed word variables at the bottom and multiple layers of latent variables on top. For each document, we first sample values for the latent variables layer by layer via logic sampling, then draw relative frequencies for the words conditioned on the values of the latent variables, and finally generate words for the document using the relative word frequencies. The motivation for the work is to take word counts into consideration with HLTMs. In comparison with LDA-based hierarchical document generation processes, the new process achieves drastically better model fit with much fewer parameters. It also yields more meaningful topics and topic hierarchies. It is the new state-of-the-art for the hierarchical topic detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.04116](http://arxiv.org/abs/1712.04116)

##### PDF
[http://arxiv.org/pdf/1712.04116](http://arxiv.org/pdf/1712.04116)

