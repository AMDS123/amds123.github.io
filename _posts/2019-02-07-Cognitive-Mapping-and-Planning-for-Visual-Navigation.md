---
layout: post
title: "Cognitive Mapping and Planning for Visual Navigation"
date: 2019-02-07 18:54:58
categories: arXiv_AI
tags: arXiv_AI
author: Saurabh Gupta, Varun Tolani, James Davidson, Sergey Levine, Rahul Sukthankar, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a neural architecture for navigation in novel environments. Our proposed architecture learns to map from first-person views and plans a sequence of actions towards goals in the environment. The Cognitive Mapper and Planner (CMP) is based on two key ideas: a) a unified joint architecture for mapping and planning, such that the mapping is driven by the needs of the task, and b) a spatial memory with the ability to plan given an incomplete set of observations about the world. CMP constructs a top-down belief map of the world and applies a differentiable neural net planner to produce the next action at each time step. The accumulated belief of the world enables the agent to track visited regions of the environment. We train and test CMP on navigation problems in simulation environments derived from scans of real world buildings. Our experiments demonstrate that CMP outperforms alternate learning-based architectures, as well as, classical mapping and path planning approaches in many cases. Furthermore, it naturally extends to semantically specified goals, such as 'going to a chair'. We also deploy CMP on physical robots in indoor environments, where it achieves reasonable performance, even though it is trained entirely in simulation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1702.03920](http://arxiv.org/abs/1702.03920)

##### PDF
[http://arxiv.org/pdf/1702.03920](http://arxiv.org/pdf/1702.03920)

