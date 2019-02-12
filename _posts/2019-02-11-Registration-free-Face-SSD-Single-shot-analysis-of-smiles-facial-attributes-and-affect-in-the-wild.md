---
layout: post
title: "Registration-free Face-SSD: Single shot analysis of smiles, facial attributes, and affect in the wild"
date: 2019-02-11 18:43:31
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Prediction Detection Face_Detection Recognition
author: Youngkyoon Jang, Hatice Gunes, Ioannis Patras
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel single shot face-related task analysis method, called Face-SSD, for detecting faces and for performing various face-related (classification/regression) tasks including smile recognition, face attribute prediction and valence-arousal estimation in the wild. Face-SSD uses a Fully Convolutional Neural Network (FCNN) to detect multiple faces of different sizes and recognise/regress one or more face-related classes. Face-SSD has two parallel branches that share the same low-level filters, one branch dealing with face detection and the other one with face analysis tasks. The outputs of both branches are spatially aligned heatmaps that are produced in parallel - therefore Face-SSD does not require that face detection, facial region extraction, size normalisation, and facial region processing are performed in subsequent steps. Our contributions are threefold: 1) Face-SSD is the first network to perform face analysis without relying on pre-processing such as face detection and registration in advance - Face-SSD is a simple and a single FCNN architecture simultaneously performing face detection and face-related task analysis - those are conventionally treated as separate consecutive tasks; 2) Face-SSD is a generalised architecture that is applicable for various face analysis tasks without modifying the network structure - this is in contrast to designing task-specific architectures; and 3) Face-SSD achieves real-time performance (21 FPS) even when detecting multiple faces and recognising multiple classes in a given image. Experimental results show that Face-SSD achieves state-of-the-art performance in various face analysis tasks by reaching a recognition accuracy of 95.76% for smile detection, 90.29% for attribute prediction, and Root Mean Square (RMS) error of 0.44 and 0.39 for valence and arousal estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04042](http://arxiv.org/abs/1902.04042)

##### PDF
[http://arxiv.org/pdf/1902.04042](http://arxiv.org/pdf/1902.04042)

