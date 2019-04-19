---
layout: post
title: "Learning a Controller Fusion Network by Online Trajectory Filtering for Vision-based UAV Racing"
date: 2019-04-18 14:23:33
categories: arXiv_CV
tags: arXiv_CV
author: Matthias M&#xfc;ller, Guohao Li, Vincent Casser, Neil Smith, Dominik L. Michels, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous UAV racing has recently emerged as an interesting research problem. The dream is to beat humans in this new fast-paced sport. A common approach is to learn an end-to-end policy that directly predicts controls from raw images by imitating an expert. However, such a policy is limited by the expert it imitates and scaling to other environments and vehicle dynamics is difficult. One approach to overcome the drawbacks of an end-to-end policy is to train a network only on the perception task and handle control with a PID or MPC controller. However, a single controller must be extensively tuned and cannot usually cover the whole state space. In this paper, we propose learning an optimized controller using a DNN that fuses multiple controllers. The network learns a robust controller with online trajectory filtering, which suppresses noisy trajectories and imperfections of individual controllers. The result is a network that is able to learn a good fusion of filtered trajectories from different controllers leading to significant improvements in overall performance. We compare our trained network to controllers it has learned from, end-to-end baselines and human pilots in a realistic simulation; our network beats all baselines in extensive experiments and approaches the performance of a professional human pilot. A video summarizing this work is available at https://youtu.be/hGKlE5X9Z5U

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08801](http://arxiv.org/abs/1904.08801)

##### PDF
[http://arxiv.org/pdf/1904.08801](http://arxiv.org/pdf/1904.08801)

