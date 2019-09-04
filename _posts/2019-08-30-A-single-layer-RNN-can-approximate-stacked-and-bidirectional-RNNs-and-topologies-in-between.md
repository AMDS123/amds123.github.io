---
layout: post
title: "A single-layer RNN can approximate stacked and bidirectional RNNs, and topologies in between"
date: 2019-08-30 18:18:04
categories: arXiv_CL
tags: arXiv_CL RNN
author: Javier S. Turek, Shailee Jain, Mihai Capota, Alexander G. Huth, Theodore L. Willke
mathjax: true
---

* content
{:toc}

##### Abstract
To enhance the expressiveness and representational capacity of recurrent neural networks (RNN), a large body of work has emerged exploring stacked architectures with additional topological modifications like shortcut connections or bidirectionality. However, choosing the best network for a particular problem requires a combinatorial search over architectures and their hyperparameters. In this work, we show that a single-layer RNN can perfectly mimic an arbitrarily deep stacked RNN under specific constraints on its weight matrix and a delay between input and output. This obviates the need to manually select hyperparameters like the number of layers. Additionally, we show that weakening weight constraints while keeping the delay gives rise to partial acausality in the single-layer RNN, much like a bidirectional network. Synthetic experiments confirm that the delayed RNN can mimic bidirectional networks in perfectly solving some acausal tasks, outperforming them in others. Finally, we show that in a challenging language processing task, the delayed RNN performs within 0.3\% of the accuracy of the bidirectional network while reducing computational costs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00021](http://arxiv.org/abs/1909.00021)

##### PDF
[http://arxiv.org/pdf/1909.00021](http://arxiv.org/pdf/1909.00021)

