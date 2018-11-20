---
layout: post
title: "Towards Easier and Faster Sequence Labeling for Natural Language Processing: A Search-based Probabilistic Online Learning Framework"
date: 2018-11-19 11:11:36
categories: arXiv_AI
tags: arXiv_AI Optimization RNN
author: Xu Sun, Shuming Ma, Yi Zhang, Xuancheng Ren
mathjax: true
---

* content
{:toc}

##### Abstract
There are two major approaches for sequence labeling. One is the probabilistic gradient-based methods such as conditional random fields (CRF) and neural networks (e.g., RNN), which have high accuracy but drawbacks: slow training, and no support of search-based optimization (which is important in many cases). The other is the search-based learning methods such as structured perceptron and margin infused relaxed algorithm (MIRA), which have fast training but also drawbacks: low accuracy, no probabilistic information, and non-convergence in real-world tasks. We propose a novel and "easy" solution, a search-based probabilistic online learning method, to address most of those issues. The method is "easy", because the optimization algorithm at the training stage is as simple as the decoding algorithm at the test stage. This method searches the output candidates, derives probabilities, and conducts efficient online learning. We show that this method with fast training and theoretical guarantee of convergence, which is easy to implement, can support search-based optimization and obtain top accuracy. Experiments on well-known tasks show that our method has better accuracy than CRF and BiLSTM\footnote{The SAPO code is released at \url{https://github.com/lancopku/SAPO}.}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1503.08381](http://arxiv.org/abs/1503.08381)

##### PDF
[http://arxiv.org/pdf/1503.08381](http://arxiv.org/pdf/1503.08381)

