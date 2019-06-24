---
layout: post
title: "Scenic: A Language for Scenario Specification and Scene Generation"
date: 2019-06-21 01:12:24
categories: arXiv_CV
tags: arXiv_CV CNN
author: Daniel J. Fremont, Tommaso Dreossi, Shromona Ghosh, Xiangyu Yue, Alberto L. Sangiovanni-Vincentelli, Sanjit A. Seshia
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new probabilistic programming language for the design and analysis of perception systems, especially those based on machine learning. Specifically, we consider the problems of training a perception system to handle rare events, testing its performance under different conditions, and debugging failures. We show how a probabilistic programming language can help address these problems by specifying distributions encoding interesting types of inputs and sampling these to generate specialized training and test sets. More generally, such languages can be used for cyber-physical systems and robotics to write environment models, an essential prerequisite to any formal analysis. In this paper, we focus on systems like autonomous cars and robots, whose environment is a "scene", a configuration of physical objects and agents. We design a domain-specific language, Scenic, for describing "scenarios" that are distributions over scenes. As a probabilistic programming language, Scenic allows assigning distributions to features of the scene, as well as declaratively imposing hard and soft constraints over the scene. We develop specialized techniques for sampling from the resulting distribution, taking advantage of the structure provided by Scenic's domain-specific syntax. Finally, we apply Scenic in a case study on a convolutional neural network designed to detect cars in road images, improving its performance beyond that achieved by state-of-the-art synthetic data generation methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.09310](http://arxiv.org/abs/1809.09310)

##### PDF
[http://arxiv.org/pdf/1809.09310](http://arxiv.org/pdf/1809.09310)

