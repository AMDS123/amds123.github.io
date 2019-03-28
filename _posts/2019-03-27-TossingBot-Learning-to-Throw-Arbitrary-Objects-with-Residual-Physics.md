---
layout: post
title: "TossingBot: Learning to Throw Arbitrary Objects with Residual Physics"
date: 2019-03-27 04:04:28
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Andy Zeng, Shuran Song, Johnny Lee, Alberto Rodriguez, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate whether a robot arm can learn to pick and throw arbitrary objects into selected boxes quickly and accurately. Throwing has the potential to increase the physical reachability and picking speed of a robot arm. However, precisely throwing arbitrary objects in unstructured settings presents many challenges: from acquiring reliable pre-throw conditions (e.g. initial pose of object in manipulator) to handling varying object-centric properties (e.g. mass distribution, friction, shape) and dynamics (e.g. aerodynamics). In this work, we propose an end-to-end formulation that jointly learns to infer control parameters for grasping and throwing motion primitives from visual observations (images of arbitrary objects in a bin) through trial and error. Within this formulation, we investigate the synergies between grasping and throwing (i.e., learning grasps that enable more accurate throws) and between simulation and deep learning (i.e., using deep networks to predict residuals on top of control parameters predicted by a physics simulator). The resulting system, TossingBot, is able to grasp and throw arbitrary objects into boxes located outside its maximum reach range at 500+ mean picks per hour (600+ grasps per hour with 85% throwing accuracy); and generalizes to new objects and target locations. Videos are available at https://tossingbot.cs.princeton.edu

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11239](http://arxiv.org/abs/1903.11239)

##### PDF
[http://arxiv.org/pdf/1903.11239](http://arxiv.org/pdf/1903.11239)

