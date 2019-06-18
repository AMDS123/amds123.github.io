---
layout: post
title: "A Temporal Sequence Learning for Action Recognition and Prediction"
date: 2019-06-17 01:33:21
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Classification Prediction Recognition
author: Sangwoo Cho, Hassan Foroosh
mathjax: true
---

* content
{:toc}

##### Abstract
In this work\footnote {This work was supported in part by the National Science Foundation under grant IIS-1212948.}, we present a method to represent a video with a sequence of words, and learn the temporal sequencing of such words as the key information for predicting and recognizing human actions. We leverage core concepts from the Natural Language Processing (NLP) literature used in sentence classification to solve the problems of action prediction and action recognition. Each frame is converted into a word that is represented as a vector using the Bag of Visual Words (BoW) encoding method. The words are then combined into a sentence to represent the video, as a sentence. The sequence of words in different actions are learned with a simple but effective Temporal Convolutional Neural Network (T-CNN) that captures the temporal sequencing of information in a video sentence. We demonstrate that a key characteristic of the proposed method is its low-latency, i.e. its ability to predict an action accurately with a partial sequence (sentence). Experiments on two datasets, \textit{UCF101} and \textit{HMDB51} show that the method on average reaches 95\% of its accuracy within half the video frames. Results, also demonstrate that our method achieves compatible state-of-the-art performance in action recognition (i.e. at the completion of the sentence) in addition to action prediction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06813](http://arxiv.org/abs/1906.06813)

##### PDF
[http://arxiv.org/pdf/1906.06813](http://arxiv.org/pdf/1906.06813)

