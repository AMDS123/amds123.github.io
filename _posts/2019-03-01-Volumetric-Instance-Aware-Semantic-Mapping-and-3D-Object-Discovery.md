---
layout: post
title: "Volumetric Instance-Aware Semantic Mapping and 3D Object Discovery"
date: 2019-03-01 12:32:46
categories: arXiv_RO
tags: arXiv_RO Segmentation Prediction
author: Margarita Grinvald, Fadri Furrer, Tonci Novkovic, Jen Jen Chung, Cesar Cadena, Roland Siegwart, Juan Nieto
mathjax: true
---

* content
{:toc}

##### Abstract
To autonomously navigate and plan interactions in real-world environments, robots require the ability to robustly perceive and map complex, unstructured surrounding scenes. Besides building an internal representation of the observed scene geometry, the key insight towards a truly functional understanding of the environment is the usage of higher-level entities during mapping, such as individual object instances. We propose an approach to incrementally build volumetric object-centric maps during online scanning with a localized RGB-D camera. First, a per-frame segmentation scheme combines an unsupervised geometric approach with instance-aware semantic object predictions. This allows us to detect and segment elements both from the set of known classes and from other, previously unseen categories. Next, a data association step tracks the predicted instances across the different frames. Finally, a map integration strategy fuses information about their 3D shape, location, and, if available, semantic class into a global volume. Evaluation on a publicly available dataset shows that the proposed approach for building instance-level semantic maps is competitive with state-of-the-art methods, while additionally able to discover objects of unseen categories. The system is further evaluated within a real-world robotic mapping setup, for which qualitative results highlight the online nature of the method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00268](http://arxiv.org/abs/1903.00268)

##### PDF
[http://arxiv.org/pdf/1903.00268](http://arxiv.org/pdf/1903.00268)

