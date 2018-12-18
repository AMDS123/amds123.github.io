---
layout: post
title: "Residual Policy Learning"
date: 2018-12-15 14:47:21
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning
author: Tom Silver, Kelsey Allen, Josh Tenenbaum, Leslie Kaelbling
mathjax: true
---

* content
{:toc}

##### Abstract
We present Residual Policy Learning (RPL): a simple method for improving nondifferentiable policies using model-free deep reinforcement learning. RPL thrives in complex robotic manipulation tasks where good but imperfect controllers are available. In these tasks, reinforcement learning from scratch remains data-inefficient or intractable, but learning a residual on top of the initial controller can yield substantial improvement. We study RPL in five challenging MuJoCo tasks involving partial observability, sensor noise, model misspecification, and controller miscalibration. By combining learning with control algorithms, RPL can perform long-horizon, sparse-reward tasks for which reinforcement learning alone fails. Moreover, we find that RPL consistently and substantially improves on the initial controllers. We argue that RPL is a promising approach for combining the complementary strengths of deep reinforcement learning and robotic control, pushing the boundaries of what either can achieve independently.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06298](http://arxiv.org/abs/1812.06298)

##### PDF
[http://arxiv.org/pdf/1812.06298](http://arxiv.org/pdf/1812.06298)

