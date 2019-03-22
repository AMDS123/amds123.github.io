---
layout: post
title: "Using Local Experiences for Global Motion Planning"
date: 2019-03-20 18:47:36
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Constantinos Chamzas, Anshumali Shrivastava, Lydia E. Kavraki
mathjax: true
---

* content
{:toc}

##### Abstract
Sampling-based planners are effective in many real-world applications such as robotics manipulation, navigation, and even protein modeling. However, it is often challenging to generate a collision-free path in environments where key areas are hard to sample. In the absence of any prior information, sampling-based planners are forced to explore uniformly or heuristically, which can lead to degraded performance. One way to improve performance is to use prior knowledge of environments to adapt the sampling strategy to the problem at hand. In this work, we decompose the workspace into local primitives, memorizing local experiences by these primitives in the form of local samplers, and store them in a database. We synthesize an efficient global sampler by retrieving local experiences relevant to the given situation. Our method transfers knowledge effectively between diverse environments that share local primitives and speeds up the performance dramatically. Our results show, in terms of solution time, an improvement of multiple orders of magnitude in two traditionally challenging high-dimensional problems compared to state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08693](http://arxiv.org/abs/1903.08693)

##### PDF
[http://arxiv.org/pdf/1903.08693](http://arxiv.org/pdf/1903.08693)

