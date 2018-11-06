---
layout: post
title: "Data2Vis: Automatic Generation of Data Visualizations Using Sequence to Sequence Recurrent Neural Networks"
date: 2018-11-02 22:02:37
categories: arXiv_AI
tags: arXiv_AI Attention RNN
author: Victor Dibia, &#xc7;a&#x11f;atay Demiralp
mathjax: true
---

* content
{:toc}

##### Abstract
Rapidly creating effective visualizations using expressive grammars is challenging for users who have limited time and limited skills in statistics and data visualization. Even high-level, dedicated visualization tools often require users to manually select among data attributes, decide which transformations to apply, and specify mappings between visual encoding variables and raw or transformed attributes. 
 In this paper we introduce Data2Vis, a neural translation model for automatically generating visualizations from given datasets. We formulate visualization generation as a sequence to sequence translation problem where data specifications are mapped to visualization specifications in a declarative language (Vega-Lite). To this end, we train a multilayered attention-based recurrent neural network (RNN) with long short-term memory (LSTM) units on a corpus of visualization specifications. 
 Qualitative results show that our model learns the vocabulary and syntax for a valid visualization specification, appropriate transformations (count, bins, mean) and how to use common data selection patterns that occur within data visualizations. Data2Vis generates visualizations that are comparable to manually-created visualizations in a fraction of the time, with potential to learn more complex visualization strategies at scale.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.03126](http://arxiv.org/abs/1804.03126)

##### PDF
[http://arxiv.org/pdf/1804.03126](http://arxiv.org/pdf/1804.03126)

