---
layout: post
title: "Making History Matter: History-Advantage Sequence Training for Visual Dialog"
date: 2019-04-17 15:09:16
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning
author: Tianhao Yang, Zheng-Jun Zha, Hanwang Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We study the multi-round response generation in visual dialog, where a response is generated according to a visually grounded conversational history. Given a triplet: an image, Q&amp;A history, and current question, all the prevailing methods follow a codec (i.e., encoder-decoder) fashion in a supervised learning paradigm: a multimodal encoder encodes the triplet into a feature vector, which is then fed into the decoder for the current answer generation, supervised by the ground-truth. However, this conventional supervised learning does NOT take into account the impact of imperfect history, violating the conversational nature of visual dialog and thus making the codec more inclined to learn history bias but not contextual reasoning. To this end, inspired by the actor-critic policy gradient in reinforcement learning, we propose a novel training paradigm called History Advantage Sequence Training (HAST). Specifically, we intentionally impose wrong answers in the history, obtaining an adverse critic, and see how the historic error impacts the codec's future behavior by History Advantage-a quantity obtained by subtracting the adverse critic from the gold reward of ground-truth history. Moreover, to make the codec more sensitive to the history, we propose a novel attention network called History-Aware Co-Attention Network (HACAN) which can be effectively trained by using HAST. Experimental results on three benchmarks: VisDial v0.9&amp;v1.0 and GuessWhat?!, show that the proposed HAST strategy consistently outperforms the state-of-the-art supervised counterparts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09326](http://arxiv.org/abs/1902.09326)

##### PDF
[http://arxiv.org/pdf/1902.09326](http://arxiv.org/pdf/1902.09326)

