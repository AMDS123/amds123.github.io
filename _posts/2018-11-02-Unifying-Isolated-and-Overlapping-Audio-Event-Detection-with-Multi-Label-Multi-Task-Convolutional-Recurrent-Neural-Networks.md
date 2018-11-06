---
layout: post
title: "Unifying Isolated and Overlapping Audio Event Detection with Multi-Label Multi-Task Convolutional Recurrent Neural Networks"
date: 2018-11-02 21:16:54
categories: arXiv_SD
tags: arXiv_SD CNN RNN Classification Detection
author: Huy Phan, Oliver Y. Ch&#xe9;n, Philipp Koch, Lam Pham, Ian McLoughlin, Alfred Mertins, Maarten De Vos
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a multi-label multi-task framework based on a convolutional recurrent neural network to unify detection of isolated and overlapping audio events. The framework leverages the power of convolutional recurrent neural network architectures; convolutional layers learn effective features over which higher recurrent layers perform sequential modelling. Furthermore, the output layer is designed to handle arbitrary degrees of event overlap. At each time step in the recurrent output sequence, an output triple is dedicated to each event category of interest to jointly model event occurrence and temporal boundaries. That is, the network jointly determines whether an event of this category occurs, and when it occurs, by estimating onset and offset positions at each recurrent time step. We then introduce three sequential losses for network training: multi-label classification loss, distance estimation loss, and confidence loss. We demonstrate good generalization on two datasets: ITC-Irst for isolated audio event detection, and TUT-SED-Synthetic-2016 for overlapping audio event detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01092](http://arxiv.org/abs/1811.01092)

##### PDF
[http://arxiv.org/pdf/1811.01092](http://arxiv.org/pdf/1811.01092)

