---
layout: post
title: "Pedestrian Tracking by Probabilistic Data Association and Correspondence Embeddings"
date: 2019-07-16 14:58:37
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Embedding CNN Deep_Learning Detection
author: Borna Bi&#x107;ani&#x107;, Marin Or&#x161;i&#x107;, Ivan Markovi&#x107;, Sini&#x161;a &#x160;egvi&#x107;, Ivan Petrovi&#x107;
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the interplay between kinematics (position and velocity) and appearance cues for establishing correspondences in multi-target pedestrian tracking. We investigate tracking-by-detection approaches based on a deep learning detector, joint integrated probabilistic data association (JIPDA), and appearance-based tracking of deep correspondence embeddings. We first addressed the fixed-camera setup by fine-tuning a convolutional detector for accurate pedestrian detection and combining it with kinematic-only JIPDA. The resulting submission ranked first on the 3DMOT2015 benchmark. However, in sequences with a moving camera and unknown ego-motion, we achieved the best results by replacing kinematic cues with global nearest neighbor tracking of deep correspondence embeddings. We trained the embeddings by fine-tuning features from the second block of ResNet-18 using angular loss extended by a margin term. We note that integrating deep correspondence embeddings directly in JIPDA did not bring significant improvement. It appears that geometry of deep correspondence embeddings for soft data association needs further investigation in order to obtain the best from both worlds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07045](http://arxiv.org/abs/1907.07045)

##### PDF
[http://arxiv.org/pdf/1907.07045](http://arxiv.org/pdf/1907.07045)

