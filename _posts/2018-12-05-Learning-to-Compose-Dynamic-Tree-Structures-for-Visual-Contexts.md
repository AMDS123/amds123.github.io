---
layout: post
title: "Learning to Compose Dynamic Tree Structures for Visual Contexts"
date: 2018-12-05 09:51:19
categories: arXiv_CV
tags: arXiv_CV QA Reinforcement_Learning RNN Relation VQA
author: Kaihua Tang, Hanwang Zhang, Baoyuan Wu, Wenhan Luo, Wei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to compose dynamic tree structures that place the objects in an image into a visual context, helping visual reasoning tasks such as scene graph generation and visual Q&amp;A. Our visual context tree model, dubbed VCTree, has two key advantages over existing structured object representations including chains and fully-connected graphs: 1) The efficient and expressive binary tree encodes the inherent parallel/hierarchical relationships among objects, e.g., "clothes" and "pants" are usually co-occur and belong to "person"; 2) the dynamic structure varies from image to image and task to task, allowing more content-/task-specific message passing among objects. To construct a VCTree, we design a score function that calculates the task-dependent validity between each object pair, and the tree is the binary version of the maximum spanning tree from the score matrix. Then, visual contexts are encoded by bidirectional TreeLSTM and decoded by task-specific models. We develop a hybrid learning procedure which integrates end-task supervised learning and the tree structure reinforcement learning, where the former's evaluation result serves as a self-critic for the latter's structure exploration. Experimental results on two benchmarks, which require reasoning over contexts: Visual Genome for scene graph generation and VQA2.0 for visual Q&amp;A, show that VCTree outperforms state-of-the-art results while discovering interpretable visual context structures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01880](http://arxiv.org/abs/1812.01880)

##### PDF
[http://arxiv.org/pdf/1812.01880](http://arxiv.org/pdf/1812.01880)

