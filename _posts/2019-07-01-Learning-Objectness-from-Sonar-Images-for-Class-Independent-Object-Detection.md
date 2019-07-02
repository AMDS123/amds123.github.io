---
layout: post
title: "Learning Objectness from Sonar Images for Class-Independent Object Detection"
date: 2019-07-01 12:46:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Matias Valdenegro-Toro
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting novel objects without class information is not trivial, as it is difficult to generalize from a small training set. This is an interesting problem for underwater robotics, as modeling marine objects is inherently more difficult in sonar images, and training data might not be available apriori. Detection proposals algorithms can be used for this purpose but usually requires a large amount of output bounding boxes. In this paper we propose the use of a fully convolutional neural network that regresses an objectness value directly from a Forward-Looking sonar image. By ranking objectness, we can produce high recall (96 %) with only 100 proposals per image. In comparison, EdgeBoxes requires 5000 proposals to achieve a slightly better recall of 97 %, while Selective Search requires 2000 proposals to achieve 95 % recall. We also show that our method outperforms a template matching baseline by a considerable margin, and is able to generalize to completely new objects. We expect that this kind of technique can be used in the field to find lost objects under the sea.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00734](http://arxiv.org/abs/1907.00734)

##### PDF
[http://arxiv.org/pdf/1907.00734](http://arxiv.org/pdf/1907.00734)

