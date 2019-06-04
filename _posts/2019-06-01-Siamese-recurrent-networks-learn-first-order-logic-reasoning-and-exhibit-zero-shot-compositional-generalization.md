---
layout: post
title: "Siamese recurrent networks learn first-order logic reasoning and exhibit zero-shot compositional generalization"
date: 2019-06-01 08:17:42
categories: arXiv_AI
tags: arXiv_AI RNN Relation Recognition
author: Mathijs Mul, Willem Zuidema
mathjax: true
---

* content
{:toc}

##### Abstract
Can neural nets learn logic? We approach this classic question with current methods, and demonstrate that recurrent neural networks can learn to recognize first order logical entailment relations between expressions. We define an artificial language in first-order predicate logic, generate a large dataset of sample 'sentences', and use an automatic theorem prover to infer the relation between random pairs of such sentences. We describe a Siamese neural architecture trained to predict the logical relation, and experiment with recurrent and recursive networks. Siamese Recurrent Networks are surprisingly successful at the entailment recognition task, reaching near perfect performance on novel sentences (consisting of known words), and even outperforming recursive networks. We report a series of experiments to test the ability of the models to perform compositional generalization. In particular, we study how they deal with sentences of unseen length, and sentences containing unseen words. We show that set-ups using LSTMs and GRUs obtain high scores on these tests, demonstrating a form of compositionality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00180](http://arxiv.org/abs/1906.00180)

##### PDF
[http://arxiv.org/pdf/1906.00180](http://arxiv.org/pdf/1906.00180)

