---
layout: post
title: "{Graph Policy Gradients for Large Scale Robot Control"
date: 2019-07-08 19:38:34
categories: arXiv_RO
tags: arXiv_RO CNN
author: Arbaaz Khan, Ekaterina Tolstaya, Alejandro Ribeiro, Vijay Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of learning policies to control a large number of homogeneous robots. To this end, we propose a new algorithm we call Graph Policy Gradients (GPG) that exploits the underlying graph symmetry among the robots. The curse of dimensionality one encounters when working with a large number of robots is mitigated by employing a graph convolutional neural (GCN) network to parametrize policies for the robots. The GCN reduces the dimensionality of the problem by learning filters that aggregate information among robots locally, similar to how a convolutional neural network is able to learn local features in an image. Through experiments on formation flying, we show that our proposed method is able to scale better than existing reinforcement methods that employ fully connected networks. More importantly, we show that by using our locally learned filters we are able to zero-shot transfer policies trained on just three robots to over hundred robots.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03822](http://arxiv.org/abs/1907.03822)

##### PDF
[http://arxiv.org/pdf/1907.03822](http://arxiv.org/pdf/1907.03822)

