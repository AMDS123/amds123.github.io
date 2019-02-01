---
layout: post
title: "Human Face Expressions from Images - 2D Face Geometry and 3D Face Local Motion versus Deep Neural Features"
date: 2019-01-31 02:32:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Classification Detection Recognition
author: Rafal Pilarczyk, Xin Chang, Wladyslaw Skarbek
mathjax: true
---

* content
{:toc}

##### Abstract
Several computer algorithms for recognition of visible human emotions are compared at the web camera scenario using CNN/MMOD face detector. The recognition refers to four face expressions: smile, surprise, anger, and neutral. At the feature extraction stage, the following three concepts of face description are confronted: (a) static 2D face geometry represented by its 68 characteristic landmarks (FP68); (b) dynamic 3D geometry defined by motion parameters for eight distinguished face parts (denoted as AU8) of personalized Candide-3 model; (c) static 2D visual description as 2D array of gray scale pixels (known as facial raw image). At the classification stage, the performance of two major models are analyzed: (a) support vector machine (SVM) with kernel options; (b) convolutional neural network (CNN) with variety of relevant tensor processing layers and blocks of them. The models are trained for frontal views of human faces while they are tested for arbitrary head poses. For geometric features, the success rate (accuracy) indicate nearly triple increase of performance of CNN with respect to SVM classifiers. For raw images, CNN outperforms in accuracy its best geometric counterpart (AU/CNN) by about 30 percent while the best SVM solutions are inferior nearly four times. For F-score the high advantage of raw/CNN over geometric/CNN and geometric/SVM is observed, as well. We conclude that contrary to CNN based emotion classifiers, the generalization capability wrt human head pose is for SVM based emotion classifiers poor.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11179](http://arxiv.org/abs/1901.11179)

##### PDF
[http://arxiv.org/pdf/1901.11179](http://arxiv.org/pdf/1901.11179)

