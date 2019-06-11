---
layout: post
title: "Boosting Soft Actor-Critic: Emphasizing Recent Experience without Forgetting the Past"
date: 2019-06-10 14:27:13
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Che Wang, Keith Ross
mathjax: true
---

* content
{:toc}

##### Abstract
Soft Actor-Critic (SAC) is an off-policy actor-critic deep reinforcement learning (DRL) algorithm based on maximum entropy reinforcement learning. By combining off-policy updates with an actor-critic formulation, SAC achieves state-of-the-art performance on a range of continuous-action benchmark tasks, outperforming prior on-policy and off-policy methods. The off-policy method employed by SAC samples data uniformly from past experience when performing parameter updates. We propose Emphasizing Recent Experience (ERE), a simple but powerful off-policy sampling technique, which emphasizes recently observed data while not forgetting the past. The ERE algorithm samples more aggressively from recent experience, and also orders the updates to ensure that updates from old data do not overwrite updates from new data. We compare vanilla SAC and SAC+ERE, and show that ERE is more sample efficient than vanilla SAC for continuous-action Mujoco tasks. We also consider combining SAC with Priority Experience Replay (PER), a scheme originally proposed for deep Q-learning which prioritizes the data based on temporal-difference (TD) error. We show that SAC+PER can marginally improve the sample efficiency performance of SAC, but much less so than SAC+ERE. Finally, we propose an algorithm which integrates ERE and PER and show that this hybrid algorithm can give the best results for some of the Mujoco tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04009](http://arxiv.org/abs/1906.04009)

##### PDF
[http://arxiv.org/pdf/1906.04009](http://arxiv.org/pdf/1906.04009)

