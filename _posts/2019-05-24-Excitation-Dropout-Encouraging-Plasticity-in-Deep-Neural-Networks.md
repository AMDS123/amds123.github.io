---
layout: post
title: "Excitation Dropout: Encouraging Plasticity in Deep Neural Networks"
date: 2019-05-24 20:21:36
categories: arXiv_CV
tags: arXiv_CV Salient Prediction Recognition
author: Andrea Zunino, Sarah Adel Bargal, Pietro Morerio, Jianming Zhang, Stan Sclaroff, Vittorio Murino
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a guided dropout regularizer for deep networks based on the evidence of a network prediction defined as the firing of neurons in specific paths. In this work, we utilize the evidence at each neuron to determine the probability of dropout, rather than dropping out neurons uniformly at random as in standard dropout. In essence, we dropout with higher probability those neurons which contribute more to decision making at training time. This approach penalizes high saliency neurons that are most relevant for model prediction, i.e. those having stronger evidence. By dropping such high-saliency neurons, the network is forced to learn alternative paths in order to maintain loss minimization, resulting in a plasticity-like behavior, a characteristic of human brains too. We demonstrate better generalization ability, an increased utilization of network neurons, and a higher resilience to network compression using several metrics over four image/video recognition benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.09092](http://arxiv.org/abs/1805.09092)

##### PDF
[http://arxiv.org/pdf/1805.09092](http://arxiv.org/pdf/1805.09092)

