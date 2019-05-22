---
layout: post
title: "Approximating probabilistic models as weighted finite automata"
date: 2019-05-21 15:36:54
categories: arXiv_CL
tags: arXiv_CL Optimization Language_Model Recognition
author: Ananda Theertha Suresh, Brian Roark, Michael Riley, Vlad Schogol
mathjax: true
---

* content
{:toc}

##### Abstract
Weighted finite automata (WFA) are often used to represent probabilistic models, such as $n$-gram language models, since they are efficient for recognition tasks in time and space. The probabilistic source to be represented as a WFA, however, may come in many forms. Given a generic probabilistic model over sequences, we propose an algorithm to approximate it as a weighted finite automaton such that the Kullback-Leiber divergence between the source model and the WFA target model is minimized. The proposed algorithm involves a counting step and a difference of convex optimization, both of which can be performed efficiently. We demonstrate the usefulness of our approach on various tasks, including distilling $n$-gram models from neural models, building compact language models, and building open-vocabulary character models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08701](http://arxiv.org/abs/1905.08701)

##### PDF
[http://arxiv.org/pdf/1905.08701](http://arxiv.org/pdf/1905.08701)

