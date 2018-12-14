---
layout: post
title: "The Pros and Cons: Rank-aware Temporal Attention for Skill Determination in Long Videos"
date: 2018-12-13 17:46:23
categories: arXiv_CV
tags: arXiv_CV Attention
author: Hazel Doughty, Walterio Mayol-Cuevas, Dima Damen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new model to determine relative skill from long videos, through learnable temporal attention modules. Previous work formulates skill determination for common tasks as a ranking problem, yet measures skill from randomly sampled video segments. We believe this approach to be limiting since many parts of the video are irrelevant to assessing skill, and there may be variability in the skill exhibited throughout a video. Assessing skill from a single section may not reflect the overall skill in the video. We propose to train rank-specific temporal attention modules, learned with only video-level supervision, using a novel rank-aware loss function. In addition to attending to task-relevant video parts, our proposed loss jointly trains two attention modules to separately attend to video parts which are indicative of higher (pros) and lower (cons) skills. We evaluate the approach on the public EPIC-Skills dataset and additionally collect and annotate a larger dataset for skill determination with five previously unexplored tasks. Our method outperforms previous approaches and classic softmax attention on both datasets by over 4% pairwise accuracy, and as much as 12% on individual tasks. We also demonstrate our model's ability to attend to rank-aware parts of the video.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05538](http://arxiv.org/abs/1812.05538)

##### PDF
[http://arxiv.org/pdf/1812.05538](http://arxiv.org/pdf/1812.05538)

