---
layout: post
title: "Predicting Video Saliency with Object-to-Motion CNN and Two-layer Convolutional LSTM"
date: 2019-01-14 18:11:58
categories: arXiv_CV
tags: arXiv_CV Salient Attention Tracking CNN RNN Prediction Relation
author: Lai Jiang, Mai Xu, Zulin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Over the past few years, deep neural networks (DNNs) have exhibited great success in predicting the saliency of images. However, there are few works that apply DNNs to predict the saliency of generic videos. In this paper, we propose a novel DNN-based video saliency prediction method. Specifically, we establish a large-scale eye-tracking database of videos (LEDOV), which provides sufficient data to train the DNN models for predicting video saliency. Through the statistical analysis of our LEDOV database, we find that human attention is normally attracted by objects, particularly moving objects or the moving parts of objects. Accordingly, we propose an object-to-motion convolutional neural network (OM-CNN) to learn spatio-temporal features for predicting the intra-frame saliency via exploring the information of both objectness and object motion. We further find from our database that there exists a temporal correlation of human attention with a smooth saliency transition across video frames. Therefore, we develop a two-layer convolutional long short-term memory (2C-LSTM) network in our DNN-based method, using the extracted features of OM-CNN as the input. Consequently, the inter-frame saliency maps of videos can be generated, which consider the transition of attention across video frames. Finally, the experimental results show that our method advances the state-of-the-art in video saliency prediction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.06316](http://arxiv.org/abs/1709.06316)

##### PDF
[http://arxiv.org/pdf/1709.06316](http://arxiv.org/pdf/1709.06316)

