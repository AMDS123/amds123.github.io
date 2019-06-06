---
layout: post
title: "Learning to Compose and Reason with Language Tree Structures for Visual Grounding"
date: 2019-06-05 02:03:55
categories: arXiv_CV
tags: arXiv_CV
author: Richang Hong, Daqing Liu, Xiaoyu Mo, Xiangnan He, Hanwang Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Grounding natural language in images, such as localizing "the black dog on the left of the tree", is one of the core problems in artificial intelligence, as it needs to comprehend the fine-grained and compositional language space. However, existing solutions rely on the association between the holistic language features and visual features, while neglect the nature of compositional reasoning implied in the language. In this paper, we propose a natural language grounding model that can automatically compose a binary tree structure for parsing the language and then perform visual reasoning along the tree in a bottom-up fashion. We call our model RVG-TREE: Recursive Grounding Tree, which is inspired by the intuition that any language expression can be recursively decomposed into two constituent parts, and the grounding confidence score can be recursively accumulated by calculating their grounding scores returned by sub-trees. RVG-TREE can be trained end-to-end by using the Straight-Through Gumbel-Softmax estimator that allows the gradients from the continuous score functions passing through the discrete tree construction. Experiments on several benchmarks show that our model achieves the state-of-the-art performance with more explainable reasoning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01784](http://arxiv.org/abs/1906.01784)

##### PDF
[http://arxiv.org/pdf/1906.01784](http://arxiv.org/pdf/1906.01784)

