---
layout: post
title: "Stable, Concurrent Controller Composition for Multi-Objective Robotic Tasks"
date: 2019-03-29 16:38:00
categories: arXiv_RO
tags: arXiv_RO
author: Anqi Li, Ching-An Cheng, Byron Boots, Magnus Egerstedt
mathjax: true
---

* content
{:toc}

##### Abstract
Robotic systems often need to consider multiple tasks concurrently. This challenge calls for control synthesis algorithms that are capable of fulfilling multiple control specifications simultaneously while maintaining the stability of the overall system. In this paper, we decompose complex, multi-objective tasks into subtasks, where individual subtask controllers are designed independently and then combined to generate the overall control policy. In particular, we adopt Riemannian Motion Policies (RMPs), a recently proposed controller structure in robotics, and, RMPflow, its associated computational framework for combining RMP controllers. We re-establish and extend the stability results of RMPflow through a rigorous Control Lyapunov Function (CLF) treatment. We then show that RMPflow can stably combine individually designed subtask controllers that satisfy certain CLF constraints. This new insight leads to an efficient CLF-based computational framework to generate stable controllers that consider all the subtasks simultaneously. Compared with the original usage of RMPflow, our framework provides users the flexibility to incorporate design heuristics through nominal controllers for the subtasks. We validate the proposed computational framework through numerical simulation and robotic implementation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12605](http://arxiv.org/abs/1903.12605)

##### PDF
[http://arxiv.org/pdf/1903.12605](http://arxiv.org/pdf/1903.12605)

