---
layout: post
title: "Multi-Stage Reinforcement Learning For Object Detection"
date: 2018-10-15 21:41:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Reinforcement_Learning Detection
author: Jonas Koenig, Simon Malberg, Martin Martens, Sebastian Niehaus, Artus Krohn-Grimberghe, Arunselvan Ramaswamy
mathjax: true
---

* content
{:toc}

##### Abstract
We present a reinforcement learning approach for detecting objects within an image. Our approach performs a step-wise deformation of a bounding box with the goal of tightly framing the object. It uses a hierarchical tree-like representation of predefined region candidates, which the agent can zoom in on. This reduces the number of region candidates that must be evaluated so that the agent can afford to compute new feature maps before each step to enhance detection quality. We compare an approach that is based purely on zoom actions with one that is extended by a second refinement stage to fine-tune the bounding box after each zoom step. We also improve the fitting ability by allowing for different aspect ratios of the bounding box. Finally, we propose different reward functions to lead to a better guidance of the agent while following its search trajectories. Experiments indicate that each of these extensions leads to more correct detections. The best performing approach comprises a zoom stage and a refinement stage, uses aspect-ratio modifying actions and is trained using a combination of three different reward metrics.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10325](https://arxiv.org/abs/1810.10325)

##### PDF
[https://arxiv.org/pdf/1810.10325](https://arxiv.org/pdf/1810.10325)

