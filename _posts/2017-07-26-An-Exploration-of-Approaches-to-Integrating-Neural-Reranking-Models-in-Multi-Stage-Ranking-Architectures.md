---
layout: post
title: "An Exploration of Approaches to Integrating Neural Reranking Models in Multi-Stage Ranking Architectures"
date: 2017-07-26 02:17:05
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Zhucheng Tu, Matt Crane, Royal Sequiera, Junchen Zhang, Jimmy Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We explore different approaches to integrating a simple convolutional neural network (CNN) with the Lucene search engine in a multi-stage ranking architecture. Our models are trained using the PyTorch deep learning toolkit, which is implemented in C/C++ with a Python frontend. One obvious integration strategy is to expose the neural network directly as a service. For this, we use Apache Thrift, a software framework for building scalable cross-language services. In exploring alternative architectures, we observe that once trained, the feedforward evaluation of neural networks is quite straightforward. Therefore, we can extract the parameters of a trained CNN from PyTorch and import the model into Java, taking advantage of the Java Deeplearning4J library for feedforward evaluation. This has the advantage that the entire end-to-end system can be implemented in Java. As a third approach, we can extract the neural network from PyTorch and "compile" it into a C++ program that exposes a Thrift service. We evaluate these alternatives in terms of performance (latency and throughput) as well as ease of integration. Experiments show that feedforward evaluation of the convolutional neural network is significantly slower in Java, while the performance of the compiled C++ network does not consistently beat the PyTorch implementation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.08275](https://arxiv.org/abs/1707.08275)

##### PDF
[https://arxiv.org/pdf/1707.08275](https://arxiv.org/pdf/1707.08275)

