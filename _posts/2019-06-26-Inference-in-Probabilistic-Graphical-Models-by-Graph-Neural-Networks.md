---
layout: post
title: "Inference in Probabilistic Graphical Models by Graph Neural Networks"
date: 2019-06-26 15:02:25
categories: arXiv_AI
tags: arXiv_AI Inference
author: KiJung Yoon, Renjie Liao, Yuwen Xiong, Lisa Zhang, Ethan Fetaya, Raquel Urtasun, Richard Zemel, Xaq Pitkow
mathjax: true
---

* content
{:toc}

##### Abstract
A fundamental computation for statistical inference and accurate decision-making is to compute the marginal probabilities or most probable states of task-relevant variables. Probabilistic graphical models can efficiently represent the structure of such complex data, but performing these inferences is generally difficult. Message-passing algorithms, such as belief propagation, are a natural way to disseminate evidence amongst correlated variables while exploiting the graph structure, but these algorithms can struggle when the conditional dependency graphs contain loops. Here we use Graph Neural Networks (GNNs) to learn a message-passing algorithm that solves these inference tasks. We first show that the architecture of GNNs is well-matched to inference tasks. We then demonstrate the efficacy of this inference approach by training GNNs on a collection of graphical models and showing that they substantially outperform belief propagation on loopy graphs. Our message-passing algorithms generalize out of the training set to larger graphs and graphs with different structure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.07710](http://arxiv.org/abs/1803.07710)

##### PDF
[http://arxiv.org/pdf/1803.07710](http://arxiv.org/pdf/1803.07710)

