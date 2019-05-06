---
layout: post
title: "NoScope: Optimizing Neural Network Queries over Video at Scale"
date: 2017-08-08 21:34:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Classification Detection
author: Daniel Kang, John Emmons, Firas Abuzaid, Peter Bailis, Matei Zaharia
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in computer vision-in the form of deep neural networks-have made it possible to query increasing volumes of video data with high accuracy. However, neural network inference is computationally expensive at scale: applying a state-of-the-art object detector in real time (i.e., 30+ frames per second) to a single video requires a $4000 GPU. In response, we present NoScope, a system for querying videos that can reduce the cost of neural network video analysis by up to three orders of magnitude via inference-optimized model search. Given a target video, object to detect, and reference neural network, NoScope automatically searches for and trains a sequence, or cascade, of models that preserves the accuracy of the reference network but is specialized to the target video and are therefore far less computationally expensive. NoScope cascades two types of models: specialized models that forego the full generality of the reference model but faithfully mimic its behavior for the target video and object; and difference detectors that highlight temporal differences across frames. We show that the optimal cascade architecture differs across videos and objects, so NoScope uses an efficient cost-based optimizer to search across models and cascades. With this approach, NoScope achieves two to three order of magnitude speed-ups (265-15,500x real-time) on binary classification tasks over fixed-angle webcam and surveillance video while maintaining accuracy within 1-5% of state-of-the-art neural networks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.02529](https://arxiv.org/abs/1703.02529)

##### PDF
[https://arxiv.org/pdf/1703.02529](https://arxiv.org/pdf/1703.02529)

