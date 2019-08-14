---
layout: post
title: "Neural Text Generation with Unlikelihood Training"
date: 2019-08-12 18:09:04
categories: arXiv_CL
tags: arXiv_CL Text_Generation
author: Sean Welleck, Ilia Kulikov, Stephen Roller, Emily Dinan, Kyunghyun Cho, Jason Weston
mathjax: true
---

* content
{:toc}

##### Abstract
Neural text generation is a key tool in natural language applications, but it is well known there are major problems at its core. In particular, standard likelihood training and decoding leads to dull and repetitive responses. While some post-hoc fixes have been proposed, in particular top-k and nucleus sampling, they do not address the fact that the token-level probabilities predicted by the model itself are poor. In this paper we show that the likelihood objective itself is at fault, resulting in a model that assigns too much probability to sequences that contain repeats and frequent words unlike the human training distribution. We propose a new objective, unlikelihood training, which forces unlikely generations to be assigned lower probability by the model. We show that both token and sequence level unlikelihood training give less repetitive, less dull text while maintaining perplexity, giving far superior generations using standard greedy or beam search. Our approach provides a strong alternative to traditional training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04319](http://arxiv.org/abs/1908.04319)

##### PDF
[http://arxiv.org/pdf/1908.04319](http://arxiv.org/pdf/1908.04319)

