---
layout: post
title: "Memory-Based Neighbourhood Embedding for Visual Recognition"
date: 2019-08-14 07:19:12
categories: arXiv_CV
tags: arXiv_CV GAN Embedding Relation Recognition
author: Suichan Li, Dapeng Chen, Bin Liu, Nenghai Yu, Rui Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Learning discriminative image feature embeddings is of great importance to visual recognition. To achieve better feature embeddings, most current methods focus on designing different network structures or loss functions, and the estimated feature embeddings are usually only related to the input images. In this paper, we propose Memory-based Neighbourhood Embedding (MNE) to enhance a general CNN feature by considering its neighbourhood. The method aims to solve two critical problems, i.e., how to acquire more relevant neighbours in the network training and how to aggregate the neighbourhood information for a more discriminative embedding. We first augment an episodic memory module into the network, which can provide more relevant neighbours for both training and testing. Then the neighbours are organized in a tree graph with the target instance as the root node. The neighbourhood information is gradually aggregated to the root node in a bottom-up manner, and aggregation weights are supervised by the class relationships between the nodes. We apply MNE on image search and few shot learning tasks. Extensive ablation studies demonstrate the effectiveness of each component, and our method significantly outperforms the state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04992](http://arxiv.org/abs/1908.04992)

##### PDF
[http://arxiv.org/pdf/1908.04992](http://arxiv.org/pdf/1908.04992)

