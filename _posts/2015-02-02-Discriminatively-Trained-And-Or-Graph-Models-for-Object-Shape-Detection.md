---
layout: post
title: "Discriminatively Trained And-Or Graph Models for Object Shape Detection"
date: 2015-02-02 02:04:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Inference Detection Recognition
author: Liang Lin, Xiaolong Wang, Wei Yang, Jian-Huang Lai
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate a novel reconfigurable part-based model, namely And-Or graph model, to recognize object shapes in images. Our proposed model consists of four layers: leaf-nodes at the bottom are local classifiers for detecting contour fragments; or-nodes above the leaf-nodes function as the switches to activate their child leaf-nodes, making the model reconfigurable during inference; and-nodes in a higher layer capture holistic shape deformations; one root-node on the top, which is also an or-node, activates one of its child and-nodes to deal with large global variations (e.g. different poses and views). We propose a novel structural optimization algorithm to discriminatively train the And-Or model from weakly annotated data. This algorithm iteratively determines the model structures (e.g. the nodes and their layouts) along with the parameter learning. On several challenging datasets, our model demonstrates the effectiveness to perform robust shape-based object detection against background clutter and outperforms the other state-of-the-art approaches. We also release a new shape database with annotations, which includes more than 1500 challenging shape instances, for recognition and detection.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1502.00341](https://arxiv.org/abs/1502.00341)

##### PDF
[https://arxiv.org/pdf/1502.00341](https://arxiv.org/pdf/1502.00341)

