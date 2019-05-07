---
layout: post
title: "NO Need to Worry about Adversarial Examples in Object Detection in Autonomous Vehicles"
date: 2017-07-12 00:09:50
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Classification Detection
author: Jiajun Lu, Hussein Sibai, Evan Fabry, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
It has been shown that most machine learning algorithms are susceptible to adversarial perturbations. Slightly perturbing an image in a carefully chosen direction in the image space may cause a trained neural network model to misclassify it. Recently, it was shown that physical adversarial examples exist: printing perturbed images then taking pictures of them would still result in misclassification. This raises security and safety concerns. However, these experiments ignore a crucial property of physical objects: the camera can view objects from different distances and at different angles. In this paper, we show experiments that suggest that current constructions of physical adversarial examples do not disrupt object detection from a moving platform. Instead, a trained neural network classifies most of the pictures taken from different distances and angles of a perturbed image correctly. We believe this is because the adversarial property of the perturbation is sensitive to the scale at which the perturbed picture is viewed, so (for example) an autonomous car will misclassify a stop sign only from a small range of distances. Our work raises an important question: can one construct examples that are adversarial for many or most viewing conditions? If so, the construction should offer very significant insights into the internal representation of patterns by deep networks. If not, there is a good prospect that adversarial examples can be reduced to a curiosity with little practical impact.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.03501](https://arxiv.org/abs/1707.03501)

##### PDF
[https://arxiv.org/pdf/1707.03501](https://arxiv.org/pdf/1707.03501)

