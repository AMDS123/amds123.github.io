---
layout: post
title: "Efficient Incremental Learning for Mobile Object Detection"
date: 2019-03-26 17:22:01
categories: arXiv_AI
tags: arXiv_AI Object_Detection Knowledge Classification Detection
author: Dawei Li, Serafettin Tasci, Shalini Ghosh, Jingwen Zhu, Junting Zhang, Larry Heck
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection models shipped with camera-equipped mobile devices cannot cover the objects of interest for every user. Therefore, the incremental learning capability is a critical feature for a robust and personalized mobile object detection system that many applications would rely on. In this paper, we present an efficient yet practical system, IMOD, to incrementally train an existing object detection model such that it can detect new object classes without losing its capability to detect old classes. The key component of IMOD is a novel incremental learning algorithm that trains end-to-end for one-stage object detection deep models only using training data of new object classes. Specifically, to avoid catastrophic forgetting, the algorithm distills three types of knowledge from the old model to mimic the old model's behavior on object classification, bounding box regression and feature extraction. In addition, since the training data for the new classes may not be available, a real-time dataset construction pipeline is designed to collect training images on-the-fly and automatically label the images with both category and bounding box annotations. We have implemented IMOD under both mobile-cloud and mobile-only setups. Experiment results show that the proposed system can learn to detect a new object class in just a few minutes, including both dataset construction and model training. In comparison, traditional fine-tuning based method may take a few hours for training, and in most cases would also need a tedious and costly manual dataset labeling step.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00781](http://arxiv.org/abs/1904.00781)

##### PDF
[http://arxiv.org/pdf/1904.00781](http://arxiv.org/pdf/1904.00781)

