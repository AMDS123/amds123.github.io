---
layout: post
title: "Learning Navigation Subroutines by Watching Videos"
date: 2019-05-29 17:50:19
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Ashish Kumar, Saurabh Gupta, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
Hierarchies are an effective way to boost sample efficiency in reinforcement learning, and computational efficiency in classical planning. However, acquiring hierarchies via hand-design (as in classical planning) is suboptimal, while acquiring them via end-to-end reward based training (as in reinforcement learning) is unstable and still prohibitively expensive. In this paper, we pursue an alternate paradigm for acquiring such hierarchical abstractions (or visuo-motor subroutines), via use of passive first person observation data. We use an inverse model trained on small amounts of interaction data to pseudo-label the passive first person videos with agent actions. Visuo-motor subroutines are acquired from these pseudo-labeled videos by learning a latent intent-conditioned policy that predicts the inferred pseudo-actions from the corresponding image observations. We demonstrate our proposed approach in context of navigation, and show that we can successfully learn consistent and diverse visuo-motor subroutines from passive first-person videos. We demonstrate the utility of our acquired visuo-motor subroutines by using them as is for exploration, and as sub-policies in a hierarchical RL framework for reaching point goals and semantic goals. We also demonstrate behavior of our subroutines in the real world, by deploying them on a real robotic platform. Project website with videos, code and data: https://ashishkumar1993.github.io/subroutines/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12612](http://arxiv.org/abs/1905.12612)

##### PDF
[http://arxiv.org/pdf/1905.12612](http://arxiv.org/pdf/1905.12612)

