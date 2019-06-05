---
layout: post
title: "Hypothesis-Driven Skill Discovery for Hierarchical Deep Reinforcement Learning"
date: 2019-05-27 13:17:35
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Caleb Chuck, Supawit Chockchowwat, Scott Niekum
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning encompasses many versatile tools for designing learning agents that can perform well on a variety of high-dimensional visual tasks, ranging from video games to robotic manipulation. However, these methods typically suffer from poor sample efficiency, partially because they strive to be largely problem-agnostic. In this work, we demonstrate the utility of a different approach that is extremely sample efficient, but limited to object-centric tasks that (approximately) obey basic physical laws. Specifically, we propose the Hypothesis Proposal and Evaluation (HyPE) algorithm, which utilizes a small set of intuitive assumptions about the behavior of objects in the physical world (or in games that mimic physics) to automatically define and learn hierarchical skills in a highly efficient manner. HyPE does this by discovering objects from raw pixel data, generating hypotheses about the controllability of observed changes in object state, and learning a hierarchy of skills that can test these hypotheses and control increasingly complex interactions with objects. We demonstrate that HyPE can dramatically improve sample efficiency when learning a high-quality pixels-to-actions policy; in the popular benchmark task, Breakout, HyPE learns an order of magnitude faster than common baseline reinforcement learning and evolutionary strategies for policy learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01408](http://arxiv.org/abs/1906.01408)

##### PDF
[http://arxiv.org/pdf/1906.01408](http://arxiv.org/pdf/1906.01408)

