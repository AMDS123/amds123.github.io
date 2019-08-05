---
layout: post
title: "DAWN: Dual Augmented Memory Network for Unsupervised Video Object Tracking"
date: 2019-08-02 09:52:57
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Object_Tracking RNN Deep_Learning Quantitative
author: Zhenmei Shi, Haoyang Fang, Yu-Wing Tai, Chi-Keung Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Psychological studies have found that human visual tracking system involves learning, memory, and planning. Despite recent successes, not many works have focused on memory and planning in deep learning based tracking. We are thus interested in memory augmented network, where an external memory remembers the evolving appearance of the target (foreground) object without backpropagation for updating weights. Our Dual Augmented Memory Network (DAWN) is unique in remembering both target and background, and using an improved attention LSTM memory to guide the focus on memorized features. DAWN is effective in unsupervised tracking in handling total occlusion, severe motion blur, abrupt changes in target appearance, multiple object instances, and similar foreground and background features. We present extensive quantitative and qualitative experimental comparison with state-of-the-art methods including top contenders in recent VOT challenges. Notably, despite the straightforward implementation, DAWN is ranked third in both VOT2016 and VOT2017 challenges with excellent success rate among all VOT fast trackers running at fps &gt; 10 in unsupervised tracking in both challenges. We propose DAWN-RPN, where we simply augment our memory and attention LSTM modules to the state-of-the-art SiamRPN, and report immediate performance gain, thus demonstrating DAWN can work well with and directly benefit other models to handle difficult cases as well.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00777](http://arxiv.org/abs/1908.00777)

##### PDF
[http://arxiv.org/pdf/1908.00777](http://arxiv.org/pdf/1908.00777)

