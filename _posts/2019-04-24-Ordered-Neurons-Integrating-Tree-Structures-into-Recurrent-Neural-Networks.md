---
layout: post
title: "Ordered Neurons: Integrating Tree Structures into Recurrent Neural Networks"
date: 2019-04-24 15:38:54
categories: arXiv_CL
tags: arXiv_CL Inference RNN Language_Model
author: Yikang Shen, Shawn Tan, Alessandro Sordoni, Aaron Courville
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language is hierarchically structured: smaller units (e.g., phrases) are nested within larger units (e.g., clauses). When a larger constituent ends, all of the smaller constituents that are nested within it must also be closed. While the standard LSTM architecture allows different neurons to track information at different time scales, it does not have an explicit bias towards modeling a hierarchy of constituents. This paper proposes to add such an inductive bias by ordering the neurons; a vector of master input and forget gates ensures that when a given neuron is updated, all the neurons that follow it in the ordering are also updated. Our novel recurrent architecture, ordered neurons LSTM (ON-LSTM), achieves good performance on four different tasks: language modeling, unsupervised parsing, targeted syntactic evaluation, and logical inference.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09536](http://arxiv.org/abs/1810.09536)

##### PDF
[http://arxiv.org/pdf/1810.09536](http://arxiv.org/pdf/1810.09536)

