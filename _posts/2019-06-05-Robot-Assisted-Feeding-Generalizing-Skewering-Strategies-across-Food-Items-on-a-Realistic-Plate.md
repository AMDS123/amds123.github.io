---
layout: post
title: "Robot-Assisted Feeding: Generalizing Skewering Strategies across Food Items on a Realistic Plate"
date: 2019-06-05 22:55:11
categories: arXiv_RO
tags: arXiv_RO
author: Ryan Feng, Youngsun Kim, Gilwoo Lee, Ethan K. Gordon, Matt Schmittle, Shivaum Kumar, Tapomayukh Bhattacharjee, Siddhartha S. Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
A robot-assisted feeding system must successfully acquire many different food items and transfer them to a user. A key challenge is the wide variation in the physical properties of food, demanding diverse acquisition strategies that are also capable of adapting to previously unseen items. Our key insight is that items with similar physical properties will exhibit similar success rates across an action space, allowing us to generalize to previously unseen items. To better understand which acquisition strategies work best for varied food items, we collected a large, rich dataset of 2450 robot bite acquisition trials for 16 food items with varying properties. Analyzing the dataset provided insights into how the food items' surrounding environment, fork pitch, and fork roll angles affect bite acquisition success. We then developed a bite acquisition framework that takes the image of a full plate as an input, uses RetinaNet to create bounding boxes around food items in the image, and then applies our skewering-position-action network (SPANet) to choose a target food item and a corresponding action so that the bite acquisition success rate is maximized. SPANet also uses the surrounding environment features of food items to predict action success rates. We used this framework to perform multiple experiments on uncluttered and cluttered plates with in-class and out-of-class food items. Results indicate that SPANet can successfully generalize skewering strategies to previously unseen food items.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02350](http://arxiv.org/abs/1906.02350)

##### PDF
[http://arxiv.org/pdf/1906.02350](http://arxiv.org/pdf/1906.02350)

