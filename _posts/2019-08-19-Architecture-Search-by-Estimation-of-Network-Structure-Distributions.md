---
layout: post
title: "Architecture Search by Estimation of Network Structure Distributions"
date: 2019-08-19 15:43:22
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Anton Muravev, Jenni Raitoharju, Moncef Gabbouj
mathjax: true
---

* content
{:toc}

##### Abstract
The influence of deep learning is continuously expanding across different domains, and its new applications are ubiquitous. The question of neural network design thus increases in importance, as traditional empirical approaches are reaching their limits. Manual design of network architectures from scratch relies heavily on trial and error, while using existing pretrained models can introduce redundancies or vulnerabilities. Automated neural architecture design is able to overcome these problems, but the most successful algorithms operate on significantly constrained design spaces, assuming the target network to consist of identical repeating blocks. We propose a probabilistic representation of a neural network structure under the assumption of independence between layer types. The probability matrix (prototype) can describe general feedforward architectures and is equivalent to the population of models, while being simple to interpret and analyze. We construct an architecture search algorithm, inspired by the estimation of distribution algorithms, to take advantage of this representation. The probability matrix is tuned towards generating high-performance models by repeatedly sampling the architectures and evaluating the corresponding networks. Our algorithm is shown to discover models which are competitive with those produced by existing architecture search methods, both in accuracy and computational costs, despite the conceptual simplicity and the comparatively limited scope of achievable designs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06886](http://arxiv.org/abs/1908.06886)

##### PDF
[http://arxiv.org/pdf/1908.06886](http://arxiv.org/pdf/1908.06886)

