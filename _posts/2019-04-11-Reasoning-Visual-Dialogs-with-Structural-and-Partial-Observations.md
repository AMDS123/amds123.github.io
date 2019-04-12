---
layout: post
title: "Reasoning Visual Dialogs with Structural and Partial Observations"
date: 2019-04-11 06:46:15
categories: arXiv_AI
tags: arXiv_AI Inference Relation
author: Zilong Zheng, Wenguan Wang, Siyuan Qi, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel model to address the task of Visual Dialog which exhibits complex dialog structures. To obtain a reasonable answer based on the current question and the dialog history, the underlying semantic dependencies between dialog entities are essential. In this paper, we explicitly formalize this task as inference in a graphical model with partially observed nodes and unknown graph structures (relations in dialog). The given dialog entities are viewed as the observed nodes. The answer to a given question is represented by a node with missing value. We first introduce an Expectation Maximization algorithm to infer both the underlying dialog structures and the missing node values (desired answers). Based on this, we proceed to propose a differentiable graph neural network (GNN) solution that approximates this process. Experiment results on the VisDial and VisDial-Q datasets show that our model outperforms comparative methods. It is also observed that our method can infer the underlying dialog structure for better dialog reasoning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05548](http://arxiv.org/abs/1904.05548)

##### PDF
[http://arxiv.org/pdf/1904.05548](http://arxiv.org/pdf/1904.05548)

