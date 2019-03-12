---
layout: post
title: "Skew-Fit: State-Covering Self-Supervised Reinforcement Learning"
date: 2019-03-08 23:32:17
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Vitchyr H. Pong, Murtaza Dalal, Steven Lin, Ashvin Nair, Shikhar Bahl, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
In standard reinforcement learning, each new skill requires a manually-designed reward function, which takes considerable manual effort and engineering. Self-supervised goal setting has the potential to automate this process, enabling an agent to propose its own goals and acquire skills that achieve these goals. However, such methods typically rely on manually-designed goal distributions, or heuristics to force the agent to explore a wide range of states. We propose a formal exploration objective for goal-reaching policies that maximizes state coverage. We show that this objective is equivalent to maximizing the entropy of the goal distribution together with goal reaching performance, where goals correspond to entire states. We present an algorithm called Skew-Fit for learning such a maximum-entropy goal distribution, and show that under certain regularity conditions, our method converges to a uniform distribution over the set of possible states, even when we do not know this set beforehand. Skew-Fit enables self-supervised agents to autonomously choose and practice diverse goals. Our experiments show that it can learn a variety of manipulation tasks from images, including opening a door with a real robot, entirely from scratch and without any manually-designed reward function.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.03698](https://arxiv.org/abs/1903.03698)

##### PDF
[https://arxiv.org/pdf/1903.03698](https://arxiv.org/pdf/1903.03698)

