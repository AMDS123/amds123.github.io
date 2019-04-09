---
layout: post
title: "Revisiting EmbodiedQA: A Simple Baseline and Beyond"
date: 2019-04-08 16:23:24
categories: arXiv_CV
tags: arXiv_CV QA
author: Yu Wu, Lu Jiang, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In Embodied Question Answering (EmbodiedQA), an agent interacts with an environment to gather necessary information for answering user questions. Existing works have laid a solid foundation towards solving this interesting problem. But the current performance, especially in navigation, suggests that EmbodiedQA might be too challenging for current approaches. In this paper, we empirically study this problem and introduce 1) a simple yet effective baseline that can be end-to-end optimized by SGD; 2) an easier and practical setting for EmbodiedQA where an agent has a chance to adapt the trained model to a new environment before it actually answers users questions. In the new setting, we randomly place a few objects in new environments, and upgrade the agent policy by a distillation network to retain the generalization ability from the trained model. On the EmbodiedQA v1 benchmark, under the standard setting, our simple baseline achieves very competitive results to the-state-of-the-art; in the new setting, we found the introduced small change in settings yields a notable gain in navigation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04166](http://arxiv.org/abs/1904.04166)

##### PDF
[http://arxiv.org/pdf/1904.04166](http://arxiv.org/pdf/1904.04166)

