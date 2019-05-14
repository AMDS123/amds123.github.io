---
layout: post
title: "Language-Conditioned Graph Networks for Relational Reasoning"
date: 2019-05-10 23:47:05
categories: arXiv_CV
tags: arXiv_CV Inference Prediction Relation
author: Ronghang Hu, Anna Rohrbach, Trevor Darrell, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
Solving grounded language tasks often requires reasoning about relationships between objects in the context of a given task. For example, to answer the question ``What color is the mug on the plate?'' we must check the color of the specific mug that satisfies the ``on'' relationship with respect to the plate. Recent work has proposed various methods capable of complex relational reasoning. However, most of their power is in the inference structure, while the scene is represented with simple local appearance features. In this paper, we take an alternate approach and build contextualized representations for objects in a visual scene to support relational reasoning. We propose a general framework of Language-Conditioned Graph Networks (LCGN), where each node represents an object, and is described by a context-aware representation from related objects through iterative message passing conditioned on the textual input. E.g., conditioning on the ``on'' relationship to the plate, the object ``mug'' gathers messages from the object ``plate'' to update its representation to ``mug on the plate'', which can be easily consumed by a simple classifier for answer prediction. We experimentally show that our LCGN approach effectively supports relational reasoning and improves performance across several tasks and datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04405](http://arxiv.org/abs/1905.04405)

##### PDF
[http://arxiv.org/pdf/1905.04405](http://arxiv.org/pdf/1905.04405)

