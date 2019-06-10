---
layout: post
title: "Multi-modal Active Learning From Human Data: A Deep Reinforcement Learning Approach"
date: 2019-06-07 13:46:15
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Ognjen Rudovic, Meiru Zhang, Bjorn Schuller, Rosalind W. Picard
mathjax: true
---

* content
{:toc}

##### Abstract
Human behavior expression and experience are inherently multi-modal, and characterized by vast individual and contextual heterogeneity. To achieve meaningful human-computer and human-robot interactions, multi-modal models of the users states (e.g., engagement) are therefore needed. Most of the existing works that try to build classifiers for the users states assume that the data to train the models are fully labeled. Nevertheless, data labeling is costly and tedious, and also prone to subjective interpretations by the human coders. This is even more pronounced when the data are multi-modal (e.g., some users are more expressive with their facial expressions, some with their voice). Thus, building models that can accurately estimate the users states during an interaction is challenging. To tackle this, we propose a novel multi-modal active learning (AL) approach that uses the notion of deep reinforcement learning (RL) to find an optimal policy for active selection of the users data, needed to train the target (modality-specific) models. We investigate different strategies for multi-modal data fusion, and show that the proposed model-level fusion coupled with RL outperforms the feature-level and modality-specific models, and the naive AL strategies such as random sampling, and the standard heuristics such as uncertainty sampling. We show the benefits of this approach on the task of engagement estimation from real-world child-robot interactions during an autism therapy. Importantly, we show that the proposed multi-modal AL approach can be used to efficiently personalize the engagement classifiers to the target user using a small amount of actively selected users data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03098](http://arxiv.org/abs/1906.03098)

##### PDF
[http://arxiv.org/pdf/1906.03098](http://arxiv.org/pdf/1906.03098)

