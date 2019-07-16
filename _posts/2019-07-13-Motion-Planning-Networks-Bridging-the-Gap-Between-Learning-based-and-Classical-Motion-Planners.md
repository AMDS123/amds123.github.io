---
layout: post
title: "Motion Planning Networks: Bridging the Gap Between Learning-based and Classical Motion Planners"
date: 2019-07-13 05:34:01
categories: arXiv_AI
tags: arXiv_AI
author: Ahmed H. Qureshi, Yinglong Miao, Anthony Simeonov, Michael C. Yip
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes Motion Planning Networks (MPNet), a computationally efficient, learning-based neural planner for solving motion planning problems. MPNet uses neural networks to learn general near-optimal heuristics for path planning in seen and unseen environments. It receives environment information as point-clouds, as well as a robot's initial and desired goal configurations and recursively calls itself to bidirectionally generate connectable paths. In addition to finding directly connectable and near-optimal paths in a single pass, we show that worst-case theoretical guarantees can be proven if we merge this neural network strategy with classical sample-based planners in a hybrid approach while still retaining significant computational and optimality improvements. To learn the MPNet models, we present an active continual learning approach that enables MPNet to learn from streaming data and actively ask for expert demonstrations when needed, drastically reducing data for training. We validate MPNet against gold-standard and state-of-the-art planning methods in a variety of problems from 2D to 7D robot configuration spaces in challenging and cluttered environments, with results showing significant and consistently stronger performance metrics, and motivating neural planning in general as a modern strategy for solving motion planning problems efficiently.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06013](http://arxiv.org/abs/1907.06013)

##### PDF
[http://arxiv.org/pdf/1907.06013](http://arxiv.org/pdf/1907.06013)

