---
layout: post
title: "The Dynamic Embedded Topic Model"
date: 2019-07-12 01:55:36
categories: arXiv_CL
tags: arXiv_CL Embedding Inference
author: Adji B. Dieng, Francisco J. R. Ruiz, David M. Blei
mathjax: true
---

* content
{:toc}

##### Abstract
Topic modeling analyzes documents to learn meaningful patterns of words. Dynamic topic models capture how these patterns vary over time for a set of documents that were collected over a large time span. We develop the dynamic embedded topic model (D-ETM), a generative model of documents that combines dynamic latent Dirichlet allocation (D-LDA) and word embeddings. The D-ETM models each word with a categorical distribution whose parameter is given by the inner product between the word embedding and an embedding representation of its assigned topic at a particular time step. The word embeddings allow the D-ETM to generalize to rare words. The D-ETM learns smooth topic trajectories by defining a random walk prior over the embeddings of the topics. We fit the D-ETM using structured amortized variational inference. On a collection of United Nations debates, we find that the D-ETM learns interpretable topics and outperforms D-LDA in terms of both topic quality and predictive performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05545](http://arxiv.org/abs/1907.05545)

##### PDF
[http://arxiv.org/pdf/1907.05545](http://arxiv.org/pdf/1907.05545)

