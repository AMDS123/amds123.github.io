---
layout: post
title: "Monte-Carlo Tree Search for Efficient Visually Guided Rearrangement Planning"
date: 2019-04-23 14:15:37
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Sergey Zagoruyko, Yann Labb&#xe9;, Igor Kalevatykh, Ivan Laptev, Justin Carpentier, Mathieu Aubry, Josef Sivic
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of visually guided rearrangement planning with many movable objects, i.e., finding a sequence of actions to move a set of objects from an initial arrangement to a desired one, while relying directly on visual inputs coming from a camera. We introduce an efficient and scalable rearrangement planning method, addressing a fundamental limitation of most existing approaches that do not scale well with the number of objects. This increased efficiency allows us to use planning in a closed loop with visual workspace analysis to build a robust rearrangement framework that can recover from errors and external perturbations. The contributions of this work are threefold. First, we develop an AlphaGo-like strategy for rearrangement planning, improving the efficiency of Monte-Carlo Tree Search (MCTS) using a policy trained from rearrangement planning examples. We show empirically that the proposed approach scales well with the number of objects. Second, in order to demonstrate the efficiency of the planner on a real robot, we adopt a state-of-the-art calibration-free visual recognition system that outputs position of a single object and extend it to estimate the state of a workspace containing multiple objects. Third, we validate the complete pipeline with several experiments on a real UR-5 robotic arm solving rearrangement planning problems with multiple movable objects and only requiring few seconds of computation to compute the plan. We also show empirically that the robot can successfully recover from errors and perturbations in the workspace. Source code and pretrained models for our work are available at https://github.com/ylabbe/rearrangement-planning

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10348](http://arxiv.org/abs/1904.10348)

##### PDF
[http://arxiv.org/pdf/1904.10348](http://arxiv.org/pdf/1904.10348)

