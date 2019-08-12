---
layout: post
title: "GPGPU Linear Complexity t-SNE Optimization"
date: 2019-08-08 20:45:40
categories: arXiv_AI
tags: arXiv_AI Embedding Optimization
author: Nicola Pezzotti, Julian Thijssen, Alexander Mordvintsev, Thomas Hollt, Baldur van Lew, Boudewijn P.F. Lelieveldt, Elmar Eisemann, Anna Vilanova
mathjax: true
---

* content
{:toc}

##### Abstract
The t-distributed Stochastic Neighbor Embedding (tSNE) algorithm has become in recent years one of the most used and insightful techniques for the exploratory data analysis of high-dimensional data. tSNE reveals clusters of high-dimensional data points at different scales while it requires only minimal tuning of its parameters. Despite these advantages, the computational complexity of the algorithm limits its application to relatively small datasets. To address this problem, several evolutions of tSNE have been developed in recent years, mainly focusing on the scalability of the similarity computations between data points. However, these contributions are insufficient to achieve interactive rates when visualizing the evolution of the tSNE embedding for large datasets. In this work, we present a novel approach to the minimization of the tSNE objective function that heavily relies on modern graphics hardware and has linear computational complexity. Our technique does not only beat the state of the art, but can even be executed on the client side in a browser. We propose to approximate the repulsion forces between data points using adaptive-resolution textures that are drawn at every iteration with WebGL. This approximation allows us to reformulate the tSNE minimization problem as a series of tensor operation that are computed with TensorFlow.js, a JavaScript library for scalable tensor computations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10817](http://arxiv.org/abs/1805.10817)

##### PDF
[http://arxiv.org/pdf/1805.10817](http://arxiv.org/pdf/1805.10817)

