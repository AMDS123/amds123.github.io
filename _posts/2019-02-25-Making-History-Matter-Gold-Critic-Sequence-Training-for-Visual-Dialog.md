---
layout: post
title: "Making History Matter: Gold-Critic Sequence Training for Visual Dialog"
date: 2019-02-25 14:58:35
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning
author: Tianhao Yang, Zheng-Jun Zha, Hanwang Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We study the multi-round response generation in visual dialog systems, where a response is generated according to a visually grounded conversational history. Given a triplet: an image, Q&amp;A history, and current question, all the prevailing methods follow a codec (ie, encoder-decoder) fashion in the supervised learning paradigm: a multimodal encoder encodes the triplet into a feature vector, which is then fed into the decoder for the current answer generation, supervised by the ground-truth answer. However, this conventional supervised learning does not take into account the impact of imperfect history in the codec training, violating the conversational nature of visual dialog and thus making the codec more inclined to learn dataset bias but not visual reasoning. To this end, inspired by the actor-critic policy gradient in reinforcement learning, we propose a novel training paradigm called Gold-Critic Sequence Training (GCST). Specifically, we intentionally impose wrong answers in the history, obtaining an adverse reward, and see how the historic error impacts the codec's future behavior by subtracting the gold-critic baseline --- reward obtained by using ground-truth history --- from the adverse reward. Moreover, to make the codec more sensitive to the history, we propose a novel attention network called Recurrent Co-Attention Network (RCAN) which can be effectively trained by using GCST. Experimental results on three benchmarks: VisDial0.9&amp;1.0 and GuessWhat?!, show that the proposed GCST strategy consistently outperforms over state-of-the-art supervised counterparts under all metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09326](http://arxiv.org/abs/1902.09326)

##### PDF
[http://arxiv.org/pdf/1902.09326](http://arxiv.org/pdf/1902.09326)

