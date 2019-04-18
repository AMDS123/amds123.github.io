---
layout: post
title: "Analysing Neural Network Topologies: a Game Theoretic Approach"
date: 2019-04-17 10:28:21
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Julian Stier, Gabriele Gianini, Michael Granitzer, Konstantin Ziegler
mathjax: true
---

* content
{:toc}

##### Abstract
Artificial Neural Networks have shown impressive success in very different application cases. Choosing a proper network architecture is a critical decision for a network's success, usually done in a manual manner. As a straightforward strategy, large, mostly fully connected architectures are selected, thereby relying on a good optimization strategy to find proper weights while at the same time avoiding overfitting. However, large parts of the final network are redundant. In the best case, large parts of the network become simply irrelevant for later inferencing. In the worst case, highly parameterized architectures hinder proper optimization and allow the easy creation of adverserial examples fooling the network. A first step in removing irrelevant architectural parts lies in identifying those parts, which requires measuring the contribution of individual components such as neurons. In previous work, heuristics based on using the weight distribution of a neuron as contribution measure have shown some success, but do not provide a proper theoretical understanding. Therefore, in our work we investigate game theoretic measures, namely the Shapley value (SV), in order to separate relevant from irrelevant parts of an artificial neural network. We begin by designing a coalitional game for an artificial neural network, where neurons form coalitions and the average contributions of neurons to coalitions yield to the Shapley value. In order to measure how well the Shapley value measures the contribution of individual neurons, we remove low-contributing neurons and measure its impact on the network performance. In our experiments we show that the Shapley value outperforms other heuristics for measuring the contribution of neurons.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08166](http://arxiv.org/abs/1904.08166)

##### PDF
[http://arxiv.org/pdf/1904.08166](http://arxiv.org/pdf/1904.08166)

