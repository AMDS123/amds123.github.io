---
layout: post
title: "Learning Where to Fixate on Foveated Images"
date: 2018-11-16 15:41:24
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Classification Deep_Learning
author: Hanxiao Wang, Venkatesh Saligrama, Stan Sclaroff, Vitaly Ablavsky
mathjax: true
---

* content
{:toc}

##### Abstract
Foveation, the ability to sequentially acquire high-acuity regions of a scene viewed initially at low-acuity, is a key property of biological vision systems. In a computer vision system, foveation is also desired to increase data efficiency and derive task-relevant features. Yet, most existing deep learning models lack the ability to foveate. In this paper, we propose a deep reinforcement learning-based foveation model, DRIFT, and apply it to challenging fine-grained classification tasks. Training of DRIFT requires only image-level category labels and encourages fixations to contain discriminative information while maintaining data efficiency. Specifically, we formulate foveation as a sequential decision-making process and train a foveation actor network with a novel Deep Deterministic Policy Gradient by Conditioned Critic and Coaching (DDPGC3) algorithm. In addition, we propose to shape the reward to provide informative feedback after each fixation to better guide the RL training. We demonstrate the effectiveness of our method on five fine-grained classification benchmark datasets, and show that the proposed approach achieves state-of-the-art performance using an order-of-magnitude fewer pixels.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06868](http://arxiv.org/abs/1811.06868)

##### PDF
[http://arxiv.org/pdf/1811.06868](http://arxiv.org/pdf/1811.06868)

