---
layout: post
title: "Energy-efficient Path Planning for Ground Robots by Combining Air and Ground Measurements"
date: 2019-07-15 05:44:38
categories: arXiv_RO
tags: arXiv_RO Segmentation
author: Minghan Wei, Volkan Isler
mathjax: true
---

* content
{:toc}

##### Abstract
As mobile robots find increasing use in outdoor applications, designing energy-efficient robot navigation algorithms is gaining importance. There are two primary approaches to energy efficient navigation: Offline approaches rely on a previously built energy map as input to a path planner. Obtaining energy maps for large environments is challenging. Alternatively, the robot can navigate in an online fashion and build the map as it navigates. Online navigation in unknown environments with only local information is still a challenging research problem. In this paper, we present a novel approach which addresses both of these challenges. Our approach starts with a segmented aerial image of the environment. We show that a coarse energy map can be built from the segmentation. However, the absolute energy value for a specific terrain type (e.g. grass) can vary across environments. Therefore, rather than using this energy map directly, we use it to build the covariance function for a Gaussian Process (GP) based representation of the environment. In the online phase, energy measurements collected during navigation are used for estimating energy profiles across the environment using GP regression. Coupled with an A*-like navigation algorithm, we show in simulations that our approach outperforms representative baseline approaches. We also present results from field experiments which demonstrate the practical applicability of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06337](http://arxiv.org/abs/1907.06337)

##### PDF
[http://arxiv.org/pdf/1907.06337](http://arxiv.org/pdf/1907.06337)

