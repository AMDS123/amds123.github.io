---
layout: post
title: "Greedy InfoMax for Biologically Plausible Self-Supervised Representation Learning"
date: 2019-05-28 13:00:46
categories: arXiv_AI
tags: arXiv_AI Represenation_Learning Classification Deep_Learning
author: Sindy L&#xf6;we, Peter O&#x27;Connor, Bastiaan S. Veeling
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel deep learning method for local self-supervised representation learning that does not require labels nor end-to-end backpropagation but exploits the natural order in data instead. Inspired by the observation that biological neural networks appear to learn without backpropagating a global error signal, we split a deep neural network into a stack of gradient-isolated modules. Each module is trained to maximize the mutual information between its consecutive outputs using the InfoNCE bound from Oord et al. [2018]. Despite this greedy training, we demonstrate that each module improves upon the output of its predecessor, and that the representations created by the top module yield highly competitive results on downstream classification tasks in the audio and visual domain. The proposal enables optimizing modules asynchronously, allowing large-scale distributed training of very deep neural networks on unlabelled datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.11786](http://arxiv.org/abs/1905.11786)

##### PDF
[http://arxiv.org/pdf/1905.11786](http://arxiv.org/pdf/1905.11786)

