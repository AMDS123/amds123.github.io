---
layout: post
title: "Tied Hidden Factors in Neural Networks for End-to-End Speaker Recognition"
date: 2018-12-27 17:07:12
categories: arXiv_SD
tags: arXiv_SD Optimization Recognition
author: Antonio Miguel, Jorge Llombart, Alfonso Ortega, Eduardo Lleida
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a method to model speaker and session variability and able to generate likelihood ratios using neural networks in an end-to-end phrase dependent speaker verification system. As in Joint Factor Analysis, the model uses tied hidden variables to model speaker and session variability and a MAP adaptation of some of the parameters of the model. In the training procedure our method jointly estimates the network parameters and the values of the speaker and channel hidden variables. This is done in a two-step backpropagation algorithm, first the network weights and factor loading matrices are updated and then the hidden variables, whose gradients are calculated by aggregating the corresponding speaker or session frames, since these hidden variables are tied. The last layer of the network is defined as a linear regression probabilistic model whose inputs are the previous layer outputs. This choice has the advantage that it produces likelihoods and additionally it can be adapted during the enrolment using MAP without the need of a gradient optimization. The decisions are made based on the ratio of the output likelihoods of two neural network models, speaker adapted and universal background model. The method was evaluated on the RSR2015 database.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11946](http://arxiv.org/abs/1812.11946)

##### PDF
[http://arxiv.org/pdf/1812.11946](http://arxiv.org/pdf/1812.11946)

