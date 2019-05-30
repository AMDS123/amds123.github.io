---
layout: post
title: "Meta-Learning Representations for Continual Learning"
date: 2019-05-29 17:09:31
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Khurram Javed, Martha White
mathjax: true
---

* content
{:toc}

##### Abstract
A continual learning agent should be able to build on top of existing knowledge to learn on new data quickly while minimizing forgetting. Current intelligent systems based on neural network function approximators arguably do the opposite---they are highly prone to forgetting and rarely trained to facilitate future learning. One reason for this poor behavior is that they learn from a representation that is not explicitly trained for these two goals. In this paper, we propose MRCL, an objective to explicitly learn representations that accelerate future learning and are robust to forgetting under online updates in continual learning. The idea is to optimize the representation such that online updates minimize error on all samples with little forgetting. We show that it is possible to learn representations that are more effective for online updating and that sparsity naturally emerges in these representations. Moreover, our method is complementary to existing continual learning strategies, like MER, which can learn more effectively from representations learned by our objective. Finally, we demonstrate that a basic online updating strategy with our learned representation is competitive with rehearsal based methods for continual learning. We release an implementation of our method at https://github.com/khurramjaved96/mrcl .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12588](http://arxiv.org/abs/1905.12588)

##### PDF
[http://arxiv.org/pdf/1905.12588](http://arxiv.org/pdf/1905.12588)

