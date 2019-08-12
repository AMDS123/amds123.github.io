---
layout: post
title: "Fully Convolutional Search Heuristic Learning for Rapid Path Planners"
date: 2019-08-09 07:27:28
categories: arXiv_RO
tags: arXiv_RO CNN
author: Yuka Ariki, Takuya Narihira
mathjax: true
---

* content
{:toc}

##### Abstract
Path-planning algorithms are an important part of a wide variety of robotic applications, such as mobile robot navigation and robot arm manipulation. However, in large search spaces in which local traps may exist, it remains challenging to reliably find a path while satisfying real-time constraints. Efforts to speed up the path search have led to the development of many practical path-planning algorithms. These algorithms often define a search heuristic to guide the search towards the goal. The heuristics should be carefully designed for each specific problem to ensure reliability in the various situations encountered in the problem. However, it is often difficult for humans to craft such robust heuristics, and the search performance often degrades under conditions that violate the heuristic assumption. Rather than manually designing the heuristics, in this work, we propose a learning approach to acquire these search heuristics. Our method represents the environment containing the obstacles as an image, and this image is fed into fully convolutional neural networks to produce a search heuristic image where every pixel represents a heuristic value (cost-to-go value to a goal) in the form of a vertex of a search graph. Training the heuristic is performed using previously collected planning results. Our preliminary experiments (2D grid world navigation experiments) demonstrate significant reduction in the search costs relative to a hand-designed heuristic.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.03343](http://arxiv.org/abs/1908.03343)

##### PDF
[http://arxiv.org/pdf/1908.03343](http://arxiv.org/pdf/1908.03343)

