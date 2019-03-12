---
layout: post
title: "HG-DAgger: Interactive Imitation Learning with Human Experts"
date: 2019-03-11 06:46:08
categories: arXiv_RO
tags: arXiv_RO
author: Michael Kelly, Chelsea Sidrane, Katherine Driggs-Campbell, Mykel J. Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
Imitation learning has proven to be useful for many real-world problems, but approaches such as behavioral cloning suffer from data mismatch and compounding error issues. One attempt to address these limitations is the DAgger algorithm, which uses the state distribution induced by the novice to sample corrective actions from the expert. Such sampling schemes, however, require the expert to provide action labels without being fully in control of the system. This can decrease safety and, when using humans as experts, is likely to degrade the quality of the collected labels due to perceived actuator lag. In this work, we propose HG-DAgger, a variant of DAgger that is more suitable for interactive imitation learning from human experts in real-world systems. In addition to training a novice policy, HG-DAgger also learns a safety threshold for a model-uncertainty-based risk metric that can be used to predict the performance of the fully trained novice in different regions of the state space. We evaluate our method on both a simulated and real-world autonomous driving task, and demonstrate improved performance over both DAgger and behavioral cloning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.02890](http://arxiv.org/abs/1810.02890)

##### PDF
[http://arxiv.org/pdf/1810.02890](http://arxiv.org/pdf/1810.02890)

