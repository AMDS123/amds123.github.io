---
layout: post
title: "Generative replay with feedback connections as a general strategy for continual learning"
date: 2019-04-17 09:20:24
categories: arXiv_AI
tags: arXiv_AI Regularization
author: Gido M. van de Ven, Andreas S. Tolias
mathjax: true
---

* content
{:toc}

##### Abstract
A major obstacle to developing artificial intelligence applications capable of true lifelong learning is that artificial neural networks quickly or catastrophically forget previously learned tasks when trained on a new one. Numerous methods for alleviating catastrophic forgetting are currently being proposed, but differences in evaluation protocols make it difficult to directly compare their performance. To enable more meaningful comparisons, here we identified three distinct scenarios for continual learning based on whether task identity is known and, if it is not, whether it needs to be inferred. Performing the split and permuted MNIST task protocols according to each of these scenarios, we found that regularization-based approaches (e.g., elastic weight consolidation) failed when task identity needed to be inferred. In contrast, generative replay combined with distillation (i.e., using class probabilities as "soft targets") achieved superior performance in all three scenarios. Addressing the issue of efficiency, we reduced the computational cost of generative replay by integrating the generative model into the main model by equipping it with generative feedback or backward connections. This Replay-through-Feedback approach substantially shortened training time with no or negligible loss in performance. We believe this to be an important first step towards making the powerful technique of generative replay scalable to real-world continual learning applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.10635](http://arxiv.org/abs/1809.10635)

##### PDF
[http://arxiv.org/pdf/1809.10635](http://arxiv.org/pdf/1809.10635)

