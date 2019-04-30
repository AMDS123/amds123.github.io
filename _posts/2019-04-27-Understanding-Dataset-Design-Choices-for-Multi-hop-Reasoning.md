---
layout: post
title: "Understanding Dataset Design Choices for Multi-hop Reasoning"
date: 2019-04-27 04:36:57
categories: arXiv_AI
tags: arXiv_AI QA Relation
author: Jifan Chen, Greg Durrett
mathjax: true
---

* content
{:toc}

##### Abstract
Learning multi-hop reasoning has been a key challenge for reading comprehension models, leading to the design of datasets that explicitly focus on it. Ideally, a model should not be able to perform well on a multi-hop question answering task without doing multi-hop reasoning. In this paper, we investigate two recently proposed datasets, WikiHop and HotpotQA. First, we explore sentence-factored models for these tasks; by design, these models cannot do multi-hop reasoning, but they are still able to solve a large number of examples in both datasets. Furthermore, we find spurious correlations in the unmasked version of WikiHop, which make it easy to achieve high performance considering only the questions and answers. Finally, we investigate one key difference between these datasets, namely span-based vs. multiple-choice formulations of the QA task. Multiple-choice versions of both datasets can be easily gamed, and two models we examine only marginally exceed a baseline in this setting. Overall, while these datasets are useful testbeds, high-performing models may not be learning as much multi-hop reasoning as previously thought.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12106](http://arxiv.org/abs/1904.12106)

##### PDF
[http://arxiv.org/pdf/1904.12106](http://arxiv.org/pdf/1904.12106)

