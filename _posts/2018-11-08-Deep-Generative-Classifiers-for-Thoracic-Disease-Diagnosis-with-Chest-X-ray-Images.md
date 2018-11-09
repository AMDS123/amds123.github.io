---
layout: post
title: "Deep Generative Classifiers for Thoracic Disease Diagnosis with Chest X-ray Images"
date: 2018-11-08 18:41:48
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Deep_Learning
author: Chengsheng Mao, Yiheng Pan, Zexian Zeng, Liang Yao, Yuan Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Thoracic diseases are very serious health problems that plague a large number of people. Chest X-ray is currently one of the most popular methods to diagnose thoracic diseases, playing an important role in the healthcare workflow. However, reading the chest X-ray images and giving an accurate diagnosis remain challenging tasks for expert radiologists. With the success of deep learning in computer vision, a growing number of deep neural network architectures were applied to chest X-ray image classification. However, most of the previous deep neural network classifiers were based on deterministic architectures which are usually very noise-sensitive and are likely to aggravate the overfitting issue. In this paper, to make a deep architecture more robust to noise and to reduce overfitting, we propose using deep generative classifiers to automatically diagnose thorax diseases from the chest X-ray images. Unlike the traditional deterministic classifier, a deep generative classifier has a distribution middle layer in the deep neural network. A sampling layer then draws a random sample from the distribution layer and input it to the following layer for classification. The classifier is generative because the class label is generated from samples of a related distribution. Through training the model with a certain amount of randomness, the deep generative classifiers are expected to be robust to noise and can reduce overfitting and then achieve good performances. We implemented our deep generative classifiers based on a number of well-known deterministic neural network architectures, and tested our models on the chest X-ray14 dataset. The results demonstrated the superiority of deep generative classifiers compared with the corresponding deep deterministic classifiers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.07436](http://arxiv.org/abs/1809.07436)

##### PDF
[http://arxiv.org/pdf/1809.07436](http://arxiv.org/pdf/1809.07436)

