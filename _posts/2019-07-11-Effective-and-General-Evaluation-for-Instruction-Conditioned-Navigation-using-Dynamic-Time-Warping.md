---
layout: post
title: "Effective and General Evaluation for Instruction Conditioned Navigation using Dynamic Time Warping"
date: 2019-07-11 18:42:03
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Gabriel Magalhaes, Vihan Jain, Alexander Ku, Eugene Ie, Jason Baldridge
mathjax: true
---

* content
{:toc}

##### Abstract
In instruction conditioned navigation, agents interpret natural language and their surroundings to navigate through an environment. Datasets for studying this task typically contain pairs of these instructions and reference trajectories. Yet, most evaluation metrics used thus far fail to properly account for the latter, relying instead on insufficient similarity comparisons. We address fundamental flaws in previously used metrics and show how Dynamic Time Warping (DTW), a long known method of measuring similarity between two time series, can be used for evaluation of navigation agents. For such, we define the normalized Dynamic Time Warping (nDTW) metric, that softly penalizes deviations from the reference path, is naturally sensitive to the order of the nodes composing each path, is suited for both continuous and graph-based evaluations, and can be efficiently calculated. Further, we define SDTW, which constrains nDTW to only successful paths. We collect human similarity judgments for simulated paths and find nDTW correlates better with human rankings than all other metrics. We also demonstrate that using nDTW as a reward signal for Reinforcement Learning navigation agents improves their performance on both the Room-to-Room (R2R) and Room-for-Room (R4R) datasets. The R4R results in particular highlight the superiority of SDTW over previous success-constrained metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05446](http://arxiv.org/abs/1907.05446)

##### PDF
[http://arxiv.org/pdf/1907.05446](http://arxiv.org/pdf/1907.05446)

