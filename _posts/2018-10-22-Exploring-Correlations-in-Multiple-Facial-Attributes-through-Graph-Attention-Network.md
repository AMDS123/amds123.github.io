---
layout: post
title: "Exploring Correlations in Multiple Facial Attributes through Graph Attention Network"
date: 2018-10-22 10:09:00
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Face Embedding Relation Recognition
author: Yan Zhang, Li Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating multiple attributes from a single facial image gives comprehensive descriptions on the high level semantics of the face. It is naturally regarded as a multi-task supervised learning problem with a single deep CNN, in which lower layers are shared, and higher ones are task-dependent with the multi-branch structure. Within the traditional deep multi-task learning (DMTL) framework, this paper intends to fully exploit the correlations among different attributes by constructing a graph. The node in graph represents the feature vector from a particular branch for a given attribute, and the edge can be defined by either the prior knowledge or the similarity between two nodes in the embedding with a fully data-driven manner. We analyze that the attention mechanism actually takes effect in the latter case, and utilize the Graph Attention Layer (GAL) for exploring on the most relevant attribute feature and refining the task-dependant feature by considering other attributes. Experiments show that by mining the correlations among attributes, our method can improve the recognition accuracy on CelebA and LFWA dataset. And it also achieves competitive performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09162](http://arxiv.org/abs/1810.09162)

##### PDF
[http://arxiv.org/pdf/1810.09162](http://arxiv.org/pdf/1810.09162)

