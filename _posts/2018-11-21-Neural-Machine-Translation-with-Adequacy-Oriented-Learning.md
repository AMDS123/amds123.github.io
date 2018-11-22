---
layout: post
title: "Neural Machine Translation with Adequacy-Oriented Learning"
date: 2018-11-21 01:48:22
categories: arXiv_AI
tags: arXiv_AI Adversarial Attention Face Reinforcement_Learning NMT Quantitative
author: Xiang Kong, Zhaopeng Tu, Shuming Shi, Eduard Hovy, Tong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Although Neural Machine Translation (NMT) models have advanced state-of-the-art performance in machine translation, they face problems like the inadequate translation. We attribute this to that the standard Maximum Likelihood Estimation (MLE) cannot judge the real translation quality due to its several limitations. In this work, we propose an adequacy-oriented learning mechanism for NMT by casting translation as a stochastic policy in Reinforcement Learning (RL), where the reward is estimated by explicitly measuring translation adequacy. Benefiting from the sequence-level training of RL strategy and a more accurate reward designed specifically for translation, our model outperforms multiple strong baselines, including (1) standard and coverage-augmented attention models with MLE-based training, and (2) advanced reinforcement and adversarial training strategies with rewards based on both word-level BLEU and character-level chrF3. Quantitative and qualitative analyses on different language pairs and NMT architectures demonstrate the effectiveness and universality of the proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08541](http://arxiv.org/abs/1811.08541)

##### PDF
[http://arxiv.org/pdf/1811.08541](http://arxiv.org/pdf/1811.08541)

