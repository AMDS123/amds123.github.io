---
layout: post
title: "Learning Ground Traversability from Simulations"
date: 2019-02-18 19:00:03
categories: arXiv_RO
tags: arXiv_RO CNN Classification
author: R. Omar Chavez-Garcia, Jerome Guzzi, Luca M. Gambardella, Alessandro Giusti
mathjax: true
---

* content
{:toc}

##### Abstract
Mobile ground robots operating on unstructured terrain must predict which areas of the environment they are able to pass in order to plan feasible paths. We address traversability estimation as a heightmap classification problem: we build a convolutional neural network that, given an image representing the heightmap of a terrain patch, predicts whether the robot will be able to traverse such patch from left to right. The classifier is trained for a specific robot model (wheeled, tracked, legged, snake-like) using simulation data on procedurally generated training terrains; the trained classifier can be applied to unseen large heightmaps to yield oriented traversability maps, and then plan traversable paths. We extensively evaluate the approach in simulation on six real-world elevation datasets, and run a real-robot validation in one indoor and one outdoor environment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.05368](http://arxiv.org/abs/1709.05368)

##### PDF
[http://arxiv.org/pdf/1709.05368](http://arxiv.org/pdf/1709.05368)

