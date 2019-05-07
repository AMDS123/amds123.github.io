---
layout: post
title: "Fully Convolutional Neural Networks for Dynamic Object Detection in Grid Maps"
date: 2017-09-10 17:06:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Detection
author: Florian Piewak, Timo Rehfeld, Michael Weber, J. Marius Zöllner
mathjax: true
---

* content
{:toc}

##### Abstract
Grid maps are widely used in robotics to represent obstacles in the environment and differentiating dynamic objects from static infrastructure is essential for many practical applications. In this work, we present a methods that uses a deep convolutional neural network (CNN) to infer whether grid cells are covering a moving object or not. Compared to tracking approaches, that use e.g. a particle filter to estimate grid cell velocities and then make a decision for individual grid cells based on this estimate, our approach uses the entire grid map as input image for a CNN that inspects a larger area around each cell and thus takes the structural appearance in the grid map into account to make a decision. Compared to our reference method, our concept yields a performance increase from 83.9% to 97.2%. A runtime optimized version of our approach yields similar improvements with an execution time of just 10 milliseconds.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1709.03139](https://arxiv.org/abs/1709.03139)

##### PDF
[https://arxiv.org/pdf/1709.03139](https://arxiv.org/pdf/1709.03139)

