---
layout: post
title: "Graphical Contrastive Losses for Scene Graph Parsing"
date: 2019-04-19 05:30:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Relation
author: Ji Zhang, Kevin J. Shih, Ahmed Elgammal, Andrew Tao, Bryan Catanzaro
mathjax: true
---

* content
{:toc}

##### Abstract
Most scene graph parsers use a two-stage pipeline to detect visual relationships: the first stage detects entities, and the second predicts the predicate for each entity pair using a softmax distribution. We find that such pipelines, trained with only a cross entropy loss over predicate classes, suffer from two common errors. The first, Entity Instance Confusion, occurs when the model confuses multiple instances of the same type of entity (e.g. multiple cups). The second, Proximal Relationship Ambiguity, arises when multiple subject-predicate-object triplets appear in close proximity with the same predicate, and the model struggles to infer the correct subject-object pairings (e.g. mis-pairing musicians and their instruments). We propose a set of contrastive loss formulations that specifically target these types of errors within the scene graph parsing problem, collectively termed the Graphical Contrastive Losses. These losses explicitly force the model to disambiguate related and unrelated instances through margin constraints specific to each type of confusion. We further construct a relationship detector, called RelDN, using the aforementioned pipeline to demonstrate the efficacy of our proposed losses. Our model outperforms the winning method of the OpenImages Relationship Detection Challenge by 4.7\% (16.5\% relative) on the test set. We also show improved results over the best previous methods on the Visual Genome and Visual Relationship Detection datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02728](http://arxiv.org/abs/1903.02728)

##### PDF
[http://arxiv.org/pdf/1903.02728](http://arxiv.org/pdf/1903.02728)

