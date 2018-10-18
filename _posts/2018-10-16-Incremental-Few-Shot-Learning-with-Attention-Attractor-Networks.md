---
layout: post
title: "Incremental Few-Shot Learning with Attention Attractor Networks"
date: 2018-10-16 18:25:17
categories: arXiv_CV
tags: arXiv_CV Review Attention Optimization Classification
author: Mengye Ren, Renjie Liao, Ethan Fetaya, Richard S. Zemel
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning classifiers are often trained to recognize a set of pre-defined classes. However, in many real applications, it is often desirable to have the flexibility of learning additional concepts, without re-training on the full training set. This paper addresses this problem, incremental few-shot learning, where a regular classification network has already been trained to recognize a set of base classes; and several extra novel classes are being considered, each with only a few labeled examples. After learning the novel classes, the model is then evaluated on the overall performance of both base and novel classes. To this end, we propose a meta-learning model, the Attention Attractor Network, which regularizes the learning of novel classes. In each episode, we train a set of new weights to recognize novel classes until they converge, and we show that the technique of recurrent back-propagation can back-propagate through the optimization process and facilitate the learning of the attractor network regularizer. We demonstrate that the learned attractor network can recognize novel classes while remembering old classes without the need to review the original training set, outperforming baselines that do not rely on an iterative optimization process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07218](http://arxiv.org/abs/1810.07218)

##### PDF
[http://arxiv.org/pdf/1810.07218](http://arxiv.org/pdf/1810.07218)

