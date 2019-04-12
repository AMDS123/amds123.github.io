---
layout: post
title: "KeyIn: Discovering Subgoal Structure with Keyframe-based Video Prediction"
date: 2019-04-11 17:55:09
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Karl Pertsch, Oleh Rybkin, Jingyun Yang, Kosta Derpanis, Joseph Lim, Kostas Daniilidis, Andrew Jaegle
mathjax: true
---

* content
{:toc}

##### Abstract
Real-world image sequences can often be naturally decomposed into a small number of frames depicting interesting, highly stochastic moments (its $\textit{keyframes}$) and the low-variance frames in between them. In image sequences depicting trajectories to a goal, keyframes can be seen as capturing the $\textit{subgoals}$ of the sequence as they depict the high-variance moments of interest that ultimately led to the goal. In this paper, we introduce a video prediction model that discovers the keyframe structure of image sequences in an unsupervised fashion. We do so using a hierarchical Keyframe-Intermediate model (KeyIn) that stochastically predicts keyframes and their offsets in time and then uses these predictions to deterministically predict the intermediate frames. We propose a differentiable formulation of this problem that allows us to train the full hierarchical model using a sequence reconstruction loss. We show that our model is able to find meaningful keyframe structure in a simulated dataset of robotic demonstrations and that these keyframes can serve as subgoals for planning. Our model outperforms other hierarchical prediction approaches for planning on a simulated pushing task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05869](http://arxiv.org/abs/1904.05869)

##### PDF
[http://arxiv.org/pdf/1904.05869](http://arxiv.org/pdf/1904.05869)

