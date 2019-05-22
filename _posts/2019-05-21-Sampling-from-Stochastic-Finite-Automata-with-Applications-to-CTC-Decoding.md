---
layout: post
title: "Sampling from Stochastic Finite Automata with Applications to CTC Decoding"
date: 2019-05-21 17:26:39
categories: arXiv_CL
tags: arXiv_CL Classification
author: Martin Jansche, Alexander Gutkin
mathjax: true
---

* content
{:toc}

##### Abstract
Stochastic finite automata arise naturally in many language and speech processing tasks. They include stochastic acceptors, which represent certain probability distributions over random strings. We consider the problem of efficient sampling: drawing random string variates from the probability distribution represented by stochastic automata and transformations of those. We show that path-sampling is effective and can be efficient if the epsilon-graph of a finite automaton is acyclic. We provide an algorithm that ensures this by conflating epsilon-cycles within strongly connected components. Sampling is also effective in the presence of non-injective transformations of strings. We illustrate this in the context of decoding for Connectionist Temporal Classification (CTC), where the predictive probabilities yield auxiliary sequences which are transformed into shorter labeling strings. We can sample efficiently from the transformed labeling distribution and use this in two different strategies for finding the most probable CTC labeling.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08760](http://arxiv.org/abs/1905.08760)

##### PDF
[http://arxiv.org/pdf/1905.08760](http://arxiv.org/pdf/1905.08760)

