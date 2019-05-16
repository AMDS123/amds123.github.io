---
layout: post
title: "GMNN: Graph Markov Neural Networks"
date: 2019-05-15 14:39:33
categories: arXiv_AI
tags: arXiv_AI CNN Represenation_Learning Classification Relation
author: Meng Qu, Yoshua Bengio, Jian Tang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies semi-supervised object classification in relational data, which is a fundamental problem in relational data modeling. The problem has been extensively studied in the literature of both statistical relational learning (e.g. relational Markov networks) and graph neural networks (e.g. graph convolutional networks). Statistical relational learning methods can effectively model the dependency of object labels through conditional random fields for collective classification, whereas graph neural networks learn effective object representations for classification through end-to-end training. In this paper, we propose the Graph Markov Neural Network (GMNN) that combines the advantages of both worlds. A GMNN models the joint distribution of object labels with a conditional random field, which can be effectively trained with the variational EM algorithm. In the E-step, one graph neural network learns effective object representations for approximating the posterior distributions of object labels. In the M-step, another graph neural network is used to model the local label dependency. Experiments on object classification, link classification, and unsupervised node representation learning show that GMNN achieves state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06214](http://arxiv.org/abs/1905.06214)

##### PDF
[http://arxiv.org/pdf/1905.06214](http://arxiv.org/pdf/1905.06214)

