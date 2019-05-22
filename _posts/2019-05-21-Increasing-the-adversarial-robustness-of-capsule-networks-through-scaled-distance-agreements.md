---
layout: post
title: "Increasing the adversarial robustness of capsule networks through scaled distance agreements"
date: 2019-05-21 16:38:48
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: David Peer, Sebastian Stabinger, Antonio Rodriguez-Sanchez
mathjax: true
---

* content
{:toc}

##### Abstract
The capsule of a capsule network represents an object or part of an object in a parse tree. An output vector of a capsule encodes the instantiation parameters such as position, size, or orientation. The most used algorithm to route vectors from the lower level layers to the upper level layers is the routing-by-agreement algorithm. This algorithm is thought to activate capsules in the network such that all active capsules form a parse tree. This parse tree structure should represent a hierarchical composition of objects that are build out of smaller objects. In this paper we introduce different metrics to evaluate the parse tree structure of capsule networks and show that the commonly used routing-by-agreement algorithm does not ensure the emergence of a parse tree. Therefore, we introduce a new routing algorithm named scaled-distance-agreement routing that calculates agreements with distances rather than the dot product. We show experimentally for different network architectures and datasets that this new calculation of the agreement ensures a parse tree structure. The novel routing algorithm is also much more robust against whitebox adversarial attacks than the original routing algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09707](http://arxiv.org/abs/1812.09707)

##### PDF
[http://arxiv.org/pdf/1812.09707](http://arxiv.org/pdf/1812.09707)

