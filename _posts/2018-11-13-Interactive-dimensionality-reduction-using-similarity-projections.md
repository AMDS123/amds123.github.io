---
layout: post
title: "Interactive dimensionality reduction using similarity projections"
date: 2018-11-13 21:21:15
categories: arXiv_CV
tags: arXiv_CV Face Embedding Transfer_Learning Optimization Classification Gradient_Descent
author: Dimitris Spathis, Nikolaos Passalis, Anastasios Tefas
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in machine learning allow us to analyze and describe the content of high-dimensional data like text, audio, images or other signals. In order to visualize that data in 2D or 3D, usually Dimensionality Reduction (DR) techniques are employed. Most of these techniques, e.g., PCA or t-SNE, produce static projections without taking into account corrections from humans or other data exploration scenarios. In this work, we propose the interactive Similarity Projection (iSP), a novel interactive DR framework based on similarity embeddings, where we form a differentiable objective based on the user interactions and perform learning using gradient descent, with an end-to-end trainable architecture. Two interaction scenarios are evaluated. First, a common methodology in multidimensional projection is to project a subset of data, arrange them in classes or clusters, and project the rest unseen dataset based on that manipulation, in a kind of semi-supervised interpolation. We report results that outperform competitive baselines in a wide range of metrics and datasets. Second, we explore the scenario of manipulating some classes, while enriching the optimization with high-dimensional neighbor information. Apart from improving classification precision and clustering on images and text documents, the new emerging structure of the projection unveils semantic manifolds. For example, on the Head Pose dataset, by just dragging the faces looking far left to the left and those looking far right to the right, all faces are re-arranged on a continuum even on the vertical axis (face up and down). This end-to-end framework can be used for fast, visual semi-supervised learning, manifold exploration, interactive domain adaptation of neural embeddings and transfer learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05531](http://arxiv.org/abs/1811.05531)

##### PDF
[http://arxiv.org/pdf/1811.05531](http://arxiv.org/pdf/1811.05531)

