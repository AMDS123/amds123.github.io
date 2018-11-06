---
layout: post
title: "Convolutional neural networks on irregular domains based on approximate vertex-domain translations"
date: 2018-11-05 13:54:48
categories: arXiv_AI
tags: arXiv_AI CNN
author: Bastien Pasdeloup, Vincent Gripon, Jean-Charles Vialatte, Dominique Pastor, Pascal Frossard
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a generalization of convolutional neural networks (CNNs) to irregular domains, through the use of a translation operator on a graph structure. In regular settings such as images, convolutional layers are designed by translating a convolutional kernel over all pixels, thus enforcing translation equivariance. In the case of general graphs however, translation is not a well-defined operation, which makes shifting a convolutional kernel not straightforward. In this article, we introduce a methodology to allow the design of convolutional layers that are adapted to signals evolving on irregular topologies, even in the absence of a natural translation. Using the designed layers, we build a CNN that we train using the initial set of signals. Contrary to other approaches that aim at extending CNNs to irregular domains, we incorporate the classical settings of CNNs for 2D signals as a particular case of our approach. Designing convolutional layers in the vertex domain directly implies weight sharing, which in other approaches is generally estimated a posteriori using heuristics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1710.10035](http://arxiv.org/abs/1710.10035)

##### PDF
[http://arxiv.org/pdf/1710.10035](http://arxiv.org/pdf/1710.10035)

