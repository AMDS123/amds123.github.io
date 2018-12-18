---
layout: post
title: "Human Pose and Path Estimation from Aerial Video using Dynamic Classifier Selection"
date: 2018-12-16 07:27:26
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation
author: Asanka G Perera, Yee Wei Law, Javaan Chahl
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of estimating human pose and trajectory by an aerial robot with a monocular camera in near real time. We present a preliminary solution whose distinguishing feature is a dynamic classifier selection architecture. In our solution, each video frame is corrected for perspective using projective transformation. Then, two alternative feature sets are used: (i) Histogram of Oriented Gradients (HOG) of the silhouette, (ii) Convolutional Neural Network (CNN) features of the RGB image. The features (HOG or CNN) are classified using a dynamic classifier. A class is defined as a pose-viewpoint pair, and a total of 64 classes are defined to represent a forward walking and turning gait sequence. Our solution provides three main advantages: (i) Classification is efficient due to dynamic selection (4-class vs. 64-class classification). (ii) Classification errors are confined to neighbors of the true view-points. (iii) The robust temporal relationship between poses is used to resolve the left-right ambiguities of human silhouettes. Experiments conducted on both fronto-parallel videos and aerial videos confirm our solution can achieve accurate pose and trajectory estimation for both scenarios. We found using HOG features provides higher accuracy than using CNN features. For example, applying the HOG-based variant of our scheme to the 'walking on a figure 8-shaped path' dataset (1652 frames) achieved estimation accuracies of 99.6% for viewpoints and 96.2% for number of poses.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06408](http://arxiv.org/abs/1812.06408)

##### PDF
[http://arxiv.org/pdf/1812.06408](http://arxiv.org/pdf/1812.06408)

