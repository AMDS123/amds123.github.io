---
layout: post
title: "An Interpretable Machine Vision Approach to Human Activity Recognition using Photoplethysmograph Sensor Data"
date: 2018-12-03 11:10:59
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Eoin Brophy, Jos&#xe9; Juan Dominguez Veiga, Zhengwei Wang, Alan F. Smeaton, Tomas E. Ward
mathjax: true
---

* content
{:toc}

##### Abstract
The current gold standard for human activity recognition (HAR) is based on the use of cameras. However, the poor scalability of camera systems renders them impractical in pursuit of the goal of wider adoption of HAR in mobile computing contexts. Consequently, researchers instead rely on wearable sensors and in particular inertial sensors. A particularly prevalent wearable is the smart watch which due to its integrated inertial and optical sensing capabilities holds great potential for realising better HAR in a non-obtrusive way. This paper seeks to simplify the wearable approach to HAR through determining if the wrist-mounted optical sensor alone typically found in a smartwatch or similar device can be used as a useful source of data for activity recognition. The approach has the potential to eliminate the need for the inertial sensing element which would in turn reduce the cost of and complexity of smartwatches and fitness trackers. This could potentially commoditise the hardware requirements for HAR while retaining the functionality of both heart rate monitoring and activity capture all from a single optical sensor. Our approach relies on the adoption of machine vision for activity recognition based on suitably scaled plots of the optical signals. We take this approach so as to produce classifications that are easily explainable and interpretable by non-technical users. More specifically, images of photoplethysmography signal time series are used to retrain the penultimate layer of a convolutional neural network which has initially been trained on the ImageNet database. We then use the 2048 dimensional features from the penultimate layer as input to a support vector machine. Results from the experiment yielded an average classification accuracy of 92.3%. This result outperforms that of an optical and inertial sensor combined (78%) and illustrates the capability of HAR systems using...

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00668](http://arxiv.org/abs/1812.00668)

##### PDF
[http://arxiv.org/pdf/1812.00668](http://arxiv.org/pdf/1812.00668)

