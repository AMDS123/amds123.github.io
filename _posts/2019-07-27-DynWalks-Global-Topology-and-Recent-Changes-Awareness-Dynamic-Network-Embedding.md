---
layout: post
title: "DynWalks: Global Topology and Recent Changes Awareness Dynamic Network Embedding"
date: 2019-07-27 19:32:33
categories: arXiv_AI
tags: arXiv_AI Attention Embedding Prediction
author: Chengbin Hou, Han Zhang, Ke Tang, Shan He
mathjax: true
---

* content
{:toc}

##### Abstract
Learning topological representation of a network in dynamic environments has recently attracted considerable attention due to the time-evolving nature of many real-world networks i.e. nodes/links might be added/removed as time goes on. Dynamic network embedding aims to learn low dimensional embeddings for unseen and seen nodes by using any currently available snapshots of a dynamic network. For seen nodes, the existing methods either treat them equally important or focus on the $k$ most affected nodes at each time step. However, the former solution is time-consuming, and the later solution that relies on incoming changes may lose the global topology---an important feature for downstream tasks. To address these challenges, we propose a dynamic network embedding method called DynWalks, which includes two key components: 1) An online network embedding framework that can dynamically and efficiently learn embeddings based on the selected nodes; 2) A novel online node selecting scheme that offers the flexible choices to balance global topology and recent changes, as well as to fulfill the real-time constraint if needed. The empirical studies on six real-world dynamic networks under three different slicing ways show that DynWalks significantly outperforms the state-of-the-art methods in graph reconstruction tasks, and obtains comparable results in link prediction tasks. Furthermore, the wall-clock time and complexity analysis demonstrate its excellent time and space efficiency. The source code of DynWalks is available at https://github.com/houchengbin/DynWalks

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11968](http://arxiv.org/abs/1907.11968)

##### PDF
[http://arxiv.org/pdf/1907.11968](http://arxiv.org/pdf/1907.11968)

