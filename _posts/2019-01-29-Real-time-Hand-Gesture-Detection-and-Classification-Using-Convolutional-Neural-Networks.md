---
layout: post
title: "Real-time Hand Gesture Detection and Classification Using Convolutional Neural Networks"
date: 2019-01-29 14:52:51
categories: arXiv_AI
tags: arXiv_AI Object_Detection CNN Classification Detection Recognition
author: Okan K&#xf6;p&#xfc;kl&#xfc;, Ahmet Gunduz, Neslihan Kose, Gerhard Rigoll
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time recognition of dynamic hand gestures from video streams is a challenging task since (i) there is no indication when a gesture starts and ends in the video, (ii) performed gestures should only be recognized once, and (iii) the entire architecture should be designed considering the memory and power budget. In this work, we address these challenges by proposing a hierarchical structure enabling offline-working convolutional neural network (CNN) architectures to operate online efficiently by using sliding window approach. The proposed architecture consists of two models: (1) A detector which is a lightweight CNN architecture to detect gestures and (2) a classifier which is a deep CNN to classify the detected gestures. In order to evaluate the single-time activations of the detected gestures, we propose to use the Levenshtein distance as an evaluation metric since it can measure misclassifications, multiple detections, and missing detections at the same time. We evaluate our architecture on two publicly available datasets - EgoGesture and NVIDIA Dynamic Hand Gesture Datasets - which require temporal detection and classification of the performed hand gestures. ResNeXt-101 model, which is used as a classifier, achieves the state-of-the-art offline classification accuracy of 94.04% and 83.82% for depth modality on EgoGesture and NVIDIA benchmarks, respectively. In real-time detection and classification, we obtain considerable early detections while achieving performances close to offline operation. The codes and pretrained models used in this work are publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10323](http://arxiv.org/abs/1901.10323)

##### PDF
[http://arxiv.org/pdf/1901.10323](http://arxiv.org/pdf/1901.10323)

