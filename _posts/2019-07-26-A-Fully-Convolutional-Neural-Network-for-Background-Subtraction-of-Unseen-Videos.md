---
layout: post
title: "A Fully-Convolutional Neural Network for Background Subtraction of Unseen Videos"
date: 2019-07-26 03:05:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN Object_Tracking Semantic_Segmentation Recognition
author: M. Ozan Tezcan, Janusz Konrad, Prakash Ishwar
mathjax: true
---

* content
{:toc}

##### Abstract
Background subtraction is a basic task in computer vision and video processing often applied as a pre-processing step for object tracking, people recognition, etc. Recently, a number of successful background subtraction algorithms have been proposed, however nearly all of the top-performing ones are supervised. Crucially, their success relies upon the availability of some annotated frames of the test video during training. Consequently, their performance on completely unseen videos is undocumented in the literature. In this work, we propose a new, supervised, background-subtraction algorithm for unseen videos (BSUV-Net) based on a fully-convolutional neural network. The input to our network consists of the current frame and two background frames captured at different time scales along with their semantic segmentation maps. In order to reduce the chance of overfitting, we also introduce a new data-augmentation technique which mitigates the impact of illumination difference between the background frames and the current frame. On the CDNet-2014 dataset, BSUV-Net outperforms state-of-the-art algorithms evaluated on unseen videos in terms of F-measure, recall and precision metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11371](http://arxiv.org/abs/1907.11371)

##### PDF
[http://arxiv.org/pdf/1907.11371](http://arxiv.org/pdf/1907.11371)

