---
layout: post
title: "Future-State Predicting LSTM for Early Surgery Type Recognition"
date: 2018-11-28 18:26:24
categories: arXiv_CV
tags: arXiv_CV CNN RNN Recognition
author: Siddharth Kannan, Gaurav Yengera, Didier Mutter, Jacques Marescaux, Nicolas Padoy
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a novel approach for the early recognition of the type of a laparoscopic surgery from its video. Early recognition algorithms can be beneficial to the development of 'smart' OR systems that can provide automatic context-aware assistance, and also enable quick database indexing. The task is however ridden with challenges specific to videos belonging to the domain of laparoscopy, such as high visual similarity across surgeries and large variations in video durations. To capture the spatio-temporal dependencies in these videos, we choose as our model a combination of a Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) network. We then propose two complementary approaches for improving early recognition performance. The first approach is a CNN fine-tuning method that encourages surgeries to be distinguished based on the initial frames of laparoscopic videos. The second approach, referred to as 'Future-State Predicting LSTM', trains an LSTM to predict information related to future frames, which helps in distinguishing between the different types of surgeries. We evaluate our approaches on a large dataset of 425 laparoscopic videos containing 9 types of surgeries (Laparo425), and achieve on average an accuracy of 75% having observed only the first 10 minutes of a surgery. These results are quite promising from a practical standpoint and also encouraging for other types of image-guided surgeries.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11727](http://arxiv.org/abs/1811.11727)

##### PDF
[http://arxiv.org/pdf/1811.11727](http://arxiv.org/pdf/1811.11727)

