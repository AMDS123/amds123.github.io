---
layout: post
title: "Feature-Based Transfer Learning for Robotic Push Manipulation"
date: 2019-05-09 15:56:52
categories: arXiv_RO
tags: arXiv_RO Face Transfer_Learning Prediction
author: Jochen St&#xfc;ber, Marek Kopicki, Claudio Zito
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a data-efficient approach to learning transferable forward models for robotic push manipulation. Our approach extends our previous work on contact-based predictors by leveraging information on the pushed object's local surface features. We test the hypothesis that, by conditioning predictions on local surface features, we can achieve generalisation across objects of different shapes. In doing so, we do not require a CAD model of the object but rather rely on a point cloud object model (PCOM). Our approach involves learning motion models that are specific to contact models. Contact models encode the contacts seen during training time and allow generating similar contacts at prediction time. Predicting on familiar ground reduces the motion models' sample complexity while using local contact information for prediction increases their transferability. In extensive experiments in simulation, our approach is capable of transfer learning for various test objects, outperforming a baseline predictor. We support those results with a proof of concept on a real robot.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03720](http://arxiv.org/abs/1905.03720)

##### PDF
[http://arxiv.org/pdf/1905.03720](http://arxiv.org/pdf/1905.03720)

