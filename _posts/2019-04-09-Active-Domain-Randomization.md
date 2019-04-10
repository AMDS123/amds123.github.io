---
layout: post
title: "Active Domain Randomization"
date: 2019-04-09 16:15:39
categories: arXiv_AI
tags: arXiv_AI
author: Bhairav Mehta, Manfred Diaz, Florian Golemo, Christopher J. Pal, Liam Paull
mathjax: true
---

* content
{:toc}

##### Abstract
Domain randomization is a popular technique for improving domain transfer, often used in a zero-shot setting when the target domain is unknown or cannot easily be used for training. In this work, we empirically examine the effects of domain randomization on agent generalization. Our experiments show that domain randomization may lead to suboptimal, high-variance policies, which we attribute to the uniform sampling of environment parameters. We propose Active Domain Randomization, a novel algorithm that learns a parameter sampling strategy. Our method looks for the most informative environment variations within the given randomization ranges by leveraging the discrepancies of policy rollouts in randomized and reference environment instances. We find that training more frequently on these instances leads to better overall agent generalization. In addition, when domain randomization and policy transfer fail, Active Domain Randomization offers more insight into the deficiencies of both the chosen parameter ranges and the learned policy, allowing for more focused debugging. Our experiments across various physics-based simulated and a real-robot task show that this enhancement leads to more robust, consistent policies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04762](http://arxiv.org/abs/1904.04762)

##### PDF
[http://arxiv.org/pdf/1904.04762](http://arxiv.org/pdf/1904.04762)

