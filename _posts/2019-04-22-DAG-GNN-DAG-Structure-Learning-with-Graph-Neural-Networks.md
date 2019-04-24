---
layout: post
title: "DAG-GNN: DAG Structure Learning with Graph Neural Networks"
date: 2019-04-22 23:58:49
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning
author: Yue Yu, Jie Chen, Tian Gao, Mo Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a faithful directed acyclic graph (DAG) from samples of a joint distribution is a challenging combinatorial problem, owing to the intractable search space superexponential in the number of graph nodes. A recent breakthrough formulates the problem as a continuous optimization with a structural constraint that ensures acyclicity (Zheng et al., 2018). The authors apply the approach to the linear structural equation model (SEM) and the least-squares loss function that are statistically well justified but nevertheless limited. Motivated by the widespread success of deep learning that is capable of capturing complex nonlinear mappings, in this work we propose a deep generative model and apply a variant of the structural constraint to learn the DAG. At the heart of the generative model is a variational autoencoder parameterized by a novel graph neural network architecture, which we coin DAG-GNN. In addition to the richer capacity, an advantage of the proposed model is that it naturally handles discrete variables as well as vector-valued ones. We demonstrate that on synthetic data sets, the proposed method learns more accurate graphs for nonlinearly generated samples; and on benchmark data sets with discrete variables, the learned graphs are reasonably close to the global optima. The code is available at \url{https://github.com/fishmoon1234/DAG-GNN}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10098](http://arxiv.org/abs/1904.10098)

##### PDF
[http://arxiv.org/pdf/1904.10098](http://arxiv.org/pdf/1904.10098)

