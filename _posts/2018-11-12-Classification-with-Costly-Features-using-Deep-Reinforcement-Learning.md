---
layout: post
title: "Classification with Costly Features using Deep Reinforcement Learning"
date: 2018-11-12 17:09:14
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Classification
author: Jarom&#xed;r Janisch, Tom&#xe1;&#x161; Pevn&#xfd;, Viliam Lis&#xfd;
mathjax: true
---

* content
{:toc}

##### Abstract
We study a classification problem where each feature can be acquired for a cost and the goal is to optimize a trade-off between the expected classification error and the feature cost. We revisit a former approach that has framed the problem as a sequential decision-making problem and solved it by Q-learning with a linear approximation, where individual actions are either requests for feature values or terminate the episode by providing a classification decision. On a set of eight problems, we demonstrate that by replacing the linear approximation with neural networks the approach becomes comparable to the state-of-the-art algorithms developed specifically for this problem. The approach is flexible, as it can be improved with any new reinforcement learning enhancement, it allows inclusion of pre-trained high-performance classifier, and unlike prior art, its performance is robust across all evaluated datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.07364](http://arxiv.org/abs/1711.07364)

##### PDF
[http://arxiv.org/pdf/1711.07364](http://arxiv.org/pdf/1711.07364)

