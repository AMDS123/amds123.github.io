---
layout: post
title: "Incorporating Structural Alternatives and Sharing into Hierarchy for Multiclass Object Recognition and Detection"
date: 2015-02-03 05:45:56
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization Classification Detection Recognition
author: Xiaolong Wang, Liang Lin, Lichao Huang, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a reconfigurable model to recognize and detect multiclass (or multiview) objects with large variation in appearance. Compared with well acknowledged hierarchical models, we study two advanced capabilities in hierarchy for object modeling: (i) "switch" variables(i.e. or-nodes) for specifying alternative compositions, and (ii) making local classifiers (i.e. leaf-nodes) shared among different classes. These capabilities enable us to account well for structural variabilities while preserving the model compact. Our model, in the form of an And-Or Graph, comprises four layers: a batch of leaf-nodes with collaborative edges in bottom for localizing object parts; the or-nodes over bottom to activate their children leaf-nodes; the and-nodes to classify objects as a whole; one root-node on the top for switching multiclass classification, which is also an or-node. For model training, we present an EM-type algorithm, namely dynamical structural optimization (DSO), to iteratively determine the structural configuration, (e.g., leaf-node generation associated with their parent or-nodes and shared across other classes), along with optimizing multi-layer parameters. The proposed method is valid on challenging databases, e.g., PASCAL VOC 2007 and UIUC-People, and it achieves state-of-the-arts performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1502.00744](https://arxiv.org/abs/1502.00744)

##### PDF
[https://arxiv.org/pdf/1502.00744](https://arxiv.org/pdf/1502.00744)

