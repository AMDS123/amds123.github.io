---
layout: post
title: "PaintBot: A Reinforcement Learning Approach for Natural Media Painting"
date: 2019-04-03 18:56:02
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Optimization
author: Biao Jia, Chen Fang, Jonathan Brandt, Byungmoon Kim, Dinesh Manocha
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new automated digital painting framework, based on a painting agent trained through reinforcement learning. To synthesize an image, the agent selects a sequence of continuous-valued actions representing primitive painting strokes, which are accumulated on a digital canvas. Action selection is guided by a given reference image, which the agent attempts to replicate subject to the limitations of the action space and the agent's learned policy. The painting agent policy is determined using a variant of proximal policy optimization reinforcement learning. During training, our agent is presented with patches sampled from an ensemble of reference images. To accelerate training convergence, we adopt a curriculum learning strategy, whereby reference patches are sampled according to how challenging they are using the current policy. We experiment with differing loss functions, including pixel-wise and perceptual loss, which have consequent differing effects on the learned policy. We demonstrate that our painting agent can learn an effective policy with a high dimensional continuous action space comprising pen pressure, width, tilt, and color, for a variety of painting styles. Through a coarse-to-fine refinement process our agent can paint arbitrarily complex images in the desired style.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02201](http://arxiv.org/abs/1904.02201)

##### PDF
[http://arxiv.org/pdf/1904.02201](http://arxiv.org/pdf/1904.02201)

