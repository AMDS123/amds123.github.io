---
layout: post
title: "Template-Based Automatic Search of Compact Semantic Segmentation Architectures"
date: 2019-04-04 06:06:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Reinforcement_Learning Semantic_Segmentation Classification
author: Vladimir Nekrasov, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic search of neural architectures for various vision and natural language tasks is becoming a prominent tool as it allows to discover high-performing structures on any dataset of interest. Nevertheless, on more difficult domains, such as dense per-pixel classification, current automatic approaches are limited in their scope - due to their strong reliance on existing image classifiers they tend to search only for a handful of additional layers with discovered architectures still containing a large number of parameters. In contrast, in this work we propose a novel solution able to find light-weight and accurate segmentation architectures starting from only few blocks of a pre-trained classification network. To this end, we progressively build up a methodology that relies on templates of sets of operations, predicts which template and how many times should be applied at each step, while also generating the connectivity structure and downsampling factors. All these decisions are being made by a recurrent neural network that is rewarded based on the score of the emitted architecture on the holdout set and trained using reinforcement learning. One discovered architecture achieves 63.2% mean IoU on CamVid and 67.8% on CityScapes having only 270K parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02365](http://arxiv.org/abs/1904.02365)

##### PDF
[http://arxiv.org/pdf/1904.02365](http://arxiv.org/pdf/1904.02365)

