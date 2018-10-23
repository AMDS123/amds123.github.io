---
layout: post
title: "Subset Scanning Over Neural Network Activations"
date: 2018-10-19 20:22:53
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN Quantitative Detection
author: Skyler Speakman, Srihari Sridharan, Sekou Remy, Komminist Weldemariam, Edward McFowland
mathjax: true
---

* content
{:toc}

##### Abstract
This work views neural networks as data generating systems and applies anomalous pattern detection techniques on that data in order to detect when a network is processing an anomalous input. Detecting anomalies is a critical component for multiple machine learning problems including detecting adversarial noise. More broadly, this work is a step towards giving neural networks the ability to recognize an out-of-distribution sample. This is the first work to introduce "Subset Scanning" methods from the anomalous pattern detection domain to the task of detecting anomalous input of neural networks. Subset scanning treats the detection problem as a search for the most anomalous subset of node activations (i.e., highest scoring subset according to non-parametric scan statistics). Mathematical properties of these scoring functions allow the search to be completed in log-linear rather than exponential time while still guaranteeing the most anomalous subset of nodes in the network is identified for a given input. Quantitative results for detecting and characterizing adversarial noise are provided for CIFAR-10 images on a simple convolutional neural network. We observe an "interference" pattern where anomalous activations in shallow layers suppress the activation structure of the original image in deeper layers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08676](http://arxiv.org/abs/1810.08676)

##### PDF
[http://arxiv.org/pdf/1810.08676](http://arxiv.org/pdf/1810.08676)

