---
layout: post
title: "Meta-Learning Multi-task Communication"
date: 2018-10-23 17:42:17
categories: arXiv_CV
tags: arXiv_CV Knowledge Quantitative
author: Pengfei Liu, Xuanjing Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe a general framework: Parameters Read-Write Networks (PRaWNs) to systematically analyze current neural models for multi-task learning, in which we find that existing models expect to disentangle features into different spaces while features learned in practice are still entangled in shared space, leaving potential hazards for other training or unseen tasks. 
 We propose to alleviate this problem by incorporating an inductive bias into the process of multi-task learning, that each task can keep informed of not only the knowledge stored in other tasks but the way how other tasks maintain their knowledge. 
 In practice, we achieve above inductive bias by allowing different tasks to communicate by passing both hidden variables and gradients explicitly. 
 Experimentally, we evaluate proposed methods on three groups of tasks and two types of settings (\textsc{in-task} and \textsc{out-of-task}). Quantitative and qualitative results show their effectiveness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09988](http://arxiv.org/abs/1810.09988)

##### PDF
[http://arxiv.org/pdf/1810.09988](http://arxiv.org/pdf/1810.09988)

