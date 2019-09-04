---
layout: post
title: "Scalable and Accurate Dialogue State Tracking via Hierarchical Sequence Generation"
date: 2019-09-02 15:00:08
categories: arXiv_AI
tags: arXiv_AI Ontology Tracking
author: Liliang Ren, Jianmo Ni, Julian McAuley
mathjax: true
---

* content
{:toc}

##### Abstract
Existing approaches to dialogue state tracking rely on pre-defined ontologies consisting of a set of all possible slot types and values. Though such approaches exhibit promising performance on single-domain benchmarks, they suffer from computational complexity that increases proportionally to the number of pre-defined slots that need tracking. This issue becomes more severe when it comes to multi-domain dialogues which include larger numbers of slots. In this paper, we investigate how to approach DST using a generation framework without the pre-defined ontology list. Given each turn of user utterance and system response, we directly generate a sequence of belief states by applying a hierarchical encoder-decoder structure. In this way, the computational complexity of our model will be a constant regardless of the number of pre-defined slots. Experiments on both the multi-domain and the single domain dialogue state tracking dataset show that our model not only scales easily with the increasing number of pre-defined domains and slots but also reaches the state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00754](http://arxiv.org/abs/1909.00754)

##### PDF
[http://arxiv.org/pdf/1909.00754](http://arxiv.org/pdf/1909.00754)

