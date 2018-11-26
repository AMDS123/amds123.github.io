---
layout: post
title: "Learning Attractor Dynamics for Generative Memory"
date: 2018-11-23 16:49:02
categories: arXiv_AI
tags: arXiv_AI Face Inference Deep_Learning
author: Yan Wu, Greg Wayne, Karol Gregor, Timothy Lillicrap
mathjax: true
---

* content
{:toc}

##### Abstract
A central challenge faced by memory systems is the robust retrieval of a stored pattern in the presence of interference due to other stored patterns and noise. A theoretically well-founded solution to robust retrieval is given by attractor dynamics, which iteratively clean up patterns during recall. However, incorporating attractor dynamics into modern deep learning systems poses difficulties: attractor basins are characterised by vanishing gradients, which are known to make training neural networks difficult. In this work, we avoid the vanishing gradient problem by training a generative distributed memory without simulating the attractor dynamics. Based on the idea of memory writing as inference, as proposed in the Kanerva Machine, we show that a likelihood-based Lyapunov function emerges from maximising the variational lower-bound of a generative memory. Experiments shows it converges to correct patterns upon iterative retrieval and achieves competitive performance as both a memory model and a generative model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09556](http://arxiv.org/abs/1811.09556)

##### PDF
[http://arxiv.org/pdf/1811.09556](http://arxiv.org/pdf/1811.09556)

