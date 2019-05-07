---
layout: post
title: "Visual-Inertial-Semantic Scene Representation for 3-D Object Detection"
date: 2017-04-17 20:25:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Drone CNN Detection
author: Jingming Dong, Xiaohan Fei, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a system to detect objects in three-dimensional space using video and inertial sensors (accelerometer and gyrometer), ubiquitous in modern mobile platforms from phones to drones. Inertials afford the ability to impose class-specific scale priors for objects, and provide a global orientation reference. A minimal sufficient representation, the posterior of semantic (identity) and syntactic (pose) attributes of objects in space, can be decomposed into a geometric term, which can be maintained by a localization-and-mapping filter, and a likelihood function, which can be approximated by a discriminatively-trained convolutional neural network. The resulting system can process the video stream causally in real time, and provides a representation of objects in the scene that is persistent: Confidence in the presence of objects grows with evidence, and objects previously seen are kept in memory even when temporarily occluded, with their return into view automatically predicted to prime re-detection.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1606.03968](https://arxiv.org/abs/1606.03968)

##### PDF
[https://arxiv.org/pdf/1606.03968](https://arxiv.org/pdf/1606.03968)

