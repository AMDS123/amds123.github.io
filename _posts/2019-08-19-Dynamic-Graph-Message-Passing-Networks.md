---
layout: post
title: "Dynamic Graph Message Passing Networks"
date: 2019-08-19 17:46:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Detection Relation
author: Li Zhang, Dan Xu, Anurag Arnab, Philip H.S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Modelling long-range dependencies is critical for complex scene understanding tasks such as semantic segmentation and object detection. Although CNNs have excelled in many computer vision tasks, they are still limited in capturing long-range structured relationships as they typically consist of layers of local kernels. A fully-connected graph is beneficial for such modelling, however, its computational overhead is prohibitive. We propose a dynamic graph message passing network, based on the message passing neural network framework, that significantly reduces the computational complexity compared to related works modelling a fully-connected graph. This is achieved by adaptively sampling nodes in the graph, conditioned on the input, for message passing. Based on the sampled nodes, we then dynamically predict node-dependent filter weights and the affinity matrix for propagating information between them. Using this model, we show significant improvements with respect to strong, state-of-the-art baselines on three different tasks and backbone architectures. Our approach also outperforms fully-connected graphs while using substantially fewer floating point operations and parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06955](http://arxiv.org/abs/1908.06955)

##### PDF
[http://arxiv.org/pdf/1908.06955](http://arxiv.org/pdf/1908.06955)

