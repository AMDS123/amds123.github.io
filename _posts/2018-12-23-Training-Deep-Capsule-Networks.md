---
layout: post
title: "Training Deep Capsule Networks"
date: 2018-12-23 13:32:59
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: David Peer, Sebastian Stabinger, Antonio Rodriguez-Sanchez
mathjax: true
---

* content
{:toc}

##### Abstract
The capsules of Capsule Networks are collections of neurons that represent an object or part of an object in a parse tree. The output vector of a capsule encodes the so called instantiation parameters of this object (e.g. position, size, or orientation). The routing-by-agreement algorithm routes output vectors from lower level capsules to upper level capsules. This iterative algorithm selects the most appropriate parent capsule so that the active capsules in the network represent nodes in a parse tree. This parse tree represents the hierarchical composition of objects out of smaller and smaller components. In this paper, we will show experimentally that the routing-by-agreement algorithm does not ensure the emergence of a parse tree in the network. To ensure that all active capsules form a parse tree, we introduce a new routing algorithm called dynamic deep routing. We show that this routing algorithm allows the training of deeper capsule networks and is also more robust to white box adversarial attacks than the original routing algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09707](http://arxiv.org/abs/1812.09707)

##### PDF
[http://arxiv.org/pdf/1812.09707](http://arxiv.org/pdf/1812.09707)

