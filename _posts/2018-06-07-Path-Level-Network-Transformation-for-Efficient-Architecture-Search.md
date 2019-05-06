---
layout: post
title: "Path-Level Network Transformation for Efficient Architecture Search"
date: 2018-06-07 12:25:05
categories: arXiv_CV
tags: arXiv_CV NAS Reinforcement_Learning Image_Classification Classification
author: Han Cai, Jiacheng Yang, Weinan Zhang, Song Han, Yong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new function-preserving transformation for efficient neural architecture search. This network transformation allows reusing previously trained networks and existing successful architectures that improves sample efficiency. We aim to address the limitation of current network transformation operations that can only perform layer-level architecture modifications, such as adding (pruning) filters or inserting (removing) a layer, which fails to change the topology of connection paths. Our proposed path-level transformation operations enable the meta-controller to modify the path topology of the given network while keeping the merits of reusing weights, and thus allow efficiently designing effective structures with complex path topologies like Inception models. We further propose a bidirectional tree-structured reinforcement learning meta-controller to explore a simple yet highly expressive tree-structured architecture space that can be viewed as a generalization of multi-branch architectures. We experimented on the image classification datasets with limited computational resources (about 200 GPU-hours), where we observed improved parameter efficiency and better test results (97.70% test accuracy on CIFAR-10 with 14.3M parameters and 74.6% top-1 accuracy on ImageNet in the mobile setting), demonstrating the effectiveness and transferability of our designed architectures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.02639](https://arxiv.org/abs/1806.02639)

##### PDF
[https://arxiv.org/pdf/1806.02639](https://arxiv.org/pdf/1806.02639)

