---
layout: post
title: "Flash Photography for Data-Driven Hidden Scene Recovery"
date: 2018-10-27 21:16:55
categories: arXiv_CV
tags: arXiv_CV
author: Matthew Tancik, Guy Satat, Ramesh Raskar
mathjax: true
---

* content
{:toc}

##### Abstract
Vehicles, search and rescue personnel, and endoscopes use flash lights to locate, identify, and view objects in their surroundings. Here we show the first steps of how all these tasks can be done around corners with consumer cameras. Recent techniques for NLOS imaging using consumer cameras have not been able to both localize and identify the hidden object. We introduce a method that couples traditional geometric understanding and data-driven techniques. To avoid the limitation of large dataset gathering, we train the data-driven models on rendered samples to computationally recover the hidden scene on real data. The method has three independent operating modes: 1) a regression output to localize a hidden object in 2D, 2) an identification output to identify the object type or pose, and 3) a generative network to reconstruct the hidden scene from a new viewpoint. The method is able to localize 12cm wide hidden objects in 2D with 1.7cm accuracy. The method also identifies the hidden object class with 87.7% accuracy (compared to 33.3% random accuracy). This paper also provides an analysis on the distribution of information that encodes the occluded object in the accessible scene. We show that, unlike previously thought, the area that extends beyond the corner is essential for accurate object localization and identification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11710](http://arxiv.org/abs/1810.11710)

##### PDF
[http://arxiv.org/pdf/1810.11710](http://arxiv.org/pdf/1810.11710)

