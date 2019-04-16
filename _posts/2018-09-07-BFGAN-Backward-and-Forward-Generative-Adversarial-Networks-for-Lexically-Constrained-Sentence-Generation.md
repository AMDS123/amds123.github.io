---
layout: post
title: "BFGAN: Backward and Forward Generative Adversarial Networks for Lexically Constrained Sentence Generation"
date: 2018-09-07 04:49:41
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Knowledge GAN Caption RNN
author: Dayiheng Liu, Jie Fu, Qian Qu, Jiancheng Lv
mathjax: true
---

* content
{:toc}

##### Abstract
Incorporating prior knowledge like lexical constraints into the model's output to generate meaningful and coherent sentences has many applications in dialogue system, machine translation, image captioning, etc. However, existing RNN-based models incrementally generate sentences from left to right via beam search, which makes it difficult to directly introduce lexical constraints into the generated sentences. In this paper, we propose a new algorithmic framework, dubbed BFGAN, to address this challenge. Specifically, we employ a backward generator and a forward generator to generate lexically constrained sentences together, and use a discriminator to guide the joint training of two generators by assigning them reward signals. Due to the difficulty of BFGAN training, we propose several training techniques to make the training process more stable and efficient. Our extensive experiments on two large-scale datasets with human evaluation demonstrate that BFGAN has significant improvements over previous methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.08097](https://arxiv.org/abs/1806.08097)

##### PDF
[https://arxiv.org/pdf/1806.08097](https://arxiv.org/pdf/1806.08097)

