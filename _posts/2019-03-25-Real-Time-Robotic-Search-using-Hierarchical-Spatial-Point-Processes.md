---
layout: post
title: "Real-Time Robotic Search using Hierarchical Spatial Point Processes"
date: 2019-03-25 16:24:45
categories: arXiv_RO
tags: arXiv_RO Inference
author: Olov Andersson, Per Sid&#xe9;n, Johan Dahlin, Patrick Doherty, Mattias Villani
mathjax: true
---

* content
{:toc}

##### Abstract
Aerial robots hold great potential for aiding Search and Rescue (SAR) efforts over large areas. Traditional approaches typically searches an area exhaustively, thereby ignoring that the density of victims varies based on predictable factors, such as the terrain, population density and the type of disaster. We present a probabilistic model to automate SAR planning, with explicit minimization of the expected time to discovery. The proposed model is a hierarchical spatial point process with three interacting spatial fields for i) the point patterns of persons in the area, ii) the probability of detecting persons and iii) the probability of injury. This structure allows inclusion of informative priors from e.g. geographic or cell phone traffic data, while falling back to latent Gaussian processes when priors are missing or inaccurate. To solve this problem in real-time, we propose a combination of fast approximate inference using Integrated Nested Laplace Approximation (INLA), and a novel Monte Carlo tree search tailored to the problem. Experiments using data simulated from real world GIS maps show that the framework outperforms traditional search strategies, and finds up to ten times more injured in the crucial first hours.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10443](http://arxiv.org/abs/1903.10443)

##### PDF
[http://arxiv.org/pdf/1903.10443](http://arxiv.org/pdf/1903.10443)

