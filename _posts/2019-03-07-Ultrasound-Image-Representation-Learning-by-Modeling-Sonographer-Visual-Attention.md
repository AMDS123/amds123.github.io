---
layout: post
title: "Ultrasound Image Representation Learning by Modeling Sonographer Visual Attention"
date: 2019-03-07 15:05:31
categories: arXiv_CV
tags: arXiv_CV Image_Caption Salient Attention Tracking CNN Transfer_Learning Represenation_Learning Prediction Detection
author: Richard Droste, Yifan Cai, Harshita Sharma, Pierre Chatelain, Lior Drukker, Aris T. Papageorghiou, J. Alison Noble
mathjax: true
---

* content
{:toc}

##### Abstract
Image representations are commonly learned from class labels, which are a simplistic approximation of human image understanding. In this paper we demonstrate that transferable representations of images can be learned without manual annotations by modeling human visual attention. The basis of our analyses is a unique gaze tracking dataset of sonographers performing routine clinical fetal anomaly screenings. Models of sonographer visual attention are learned by training a convolutional neural network (CNN) to predict gaze on ultrasound video frames through visual saliency prediction or gaze-point regression. We evaluate the transferability of the learned representations to the task of ultrasound standard plane detection in two contexts. Firstly, we perform transfer learning by fine-tuning the CNN with a limited number of labeled standard plane images. We find that fine-tuning the saliency predictor is superior to training from random initialization, with an average F1-score improvement of 9.6% overall and 15.3% for the cardiac planes. Secondly, we train a simple softmax regression on the feature activations of each CNN layer in order to evaluate the representations independently of transfer learning hyper-parameters. We find that the attention models derive strong representations, approaching the precision of a fully-supervised baseline model for all but the last layer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02974](http://arxiv.org/abs/1903.02974)

##### PDF
[http://arxiv.org/pdf/1903.02974](http://arxiv.org/pdf/1903.02974)

