---
layout: post
title: "Toward Multimodal Image-to-Image Translation"
date: 2018-10-24 00:29:43
categories: arXiv_CV
tags: arXiv_CV
author: Jun-Yan Zhu, Richard Zhang, Deepak Pathak, Trevor Darrell, Alexei A. Efros, Oliver Wang, Eli Shechtman
mathjax: true
---

* content
{:toc}

##### Abstract
Many image-to-image translation problems are ambiguous, as a single input image may correspond to multiple possible outputs. In this work, we aim to model a \emph{distribution} of possible outputs in a conditional generative modeling setting. The ambiguity of the mapping is distilled in a low-dimensional latent vector, which can be randomly sampled at test time. A generator learns to map the given input, combined with this latent code, to the output. We explicitly encourage the connection between output and the latent code to be invertible. This helps prevent a many-to-one mapping from the latent code to the output during training, also known as the problem of mode collapse, and produces more diverse results. We explore several variants of this approach by employing different training objectives, network architectures, and methods of injecting the latent code. Our proposed method encourages bijective consistency between the latent encoding and output modes. We present a systematic comparison of our method and other variants on both perceptual realism and diversity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.11586](http://arxiv.org/abs/1711.11586)

##### PDF
[http://arxiv.org/pdf/1711.11586](http://arxiv.org/pdf/1711.11586)

