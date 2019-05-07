---
layout: post
title: "Edge-labeling Graph Neural Network for Few-shot Learning"
date: 2019-05-04 05:58:17
categories: arXiv_CV
tags: arXiv_CV Image_Classification Inference Classification
author: Jongmin Kim, Taesup Kim, Sungwoong Kim, Chang D. Yoo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel edge-labeling graph neural network (EGNN), which adapts a deep neural network on the edge-labeling graph, for few-shot learning. The previous graph neural network (GNN) approaches in few-shot learning have been based on the node-labeling framework, which implicitly models the intra-cluster similarity and the inter-cluster dissimilarity. In contrast, the proposed EGNN learns to predict the edge-labels rather than the node-labels on the graph that enables the evolution of an explicit clustering by iteratively updating the edge-labels with direct exploitation of both intra-cluster similarity and the inter-cluster dissimilarity. It is also well suited for performing on various numbers of classes without retraining, and can be easily extended to perform a transductive inference. The parameters of the EGNN are learned by episodic training with an edge-labeling loss to obtain a well-generalizable model for unseen low-data problem. On both of the supervised and semi-supervised few-shot image classification tasks with two benchmark datasets, the proposed EGNN significantly improves the performances over the existing GNNs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01436](http://arxiv.org/abs/1905.01436)

##### PDF
[http://arxiv.org/pdf/1905.01436](http://arxiv.org/pdf/1905.01436)

