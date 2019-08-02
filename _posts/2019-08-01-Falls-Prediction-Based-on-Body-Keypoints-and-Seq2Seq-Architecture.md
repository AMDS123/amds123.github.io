---
layout: post
title: "Falls Prediction Based on Body Keypoints and Seq2Seq Architecture"
date: 2019-08-01 08:54:56
categories: arXiv_CV
tags: arXiv_CV Classification Prediction Recognition
author: Minjie Hua, Yibing Nan, Shiguo Lian
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel approach for predicting falls event in advance based on the human pose. First, every person in consecutive frames are detected and tracked. And their body keypoints are extracted and then normalized for later processing. Next, the observed keypoint sequence of each person is input to a sequence-to-sequence(seq2seq) based model to predict the future keypoint sequence, which is used for falls classification to judge whether the person will fall down in the future. The action prediction module and falls classifier are trained separately and tuned jointly. The proposed model is evaluated on Le2i dataset, which is composed of 191 videos including various normal daily activities and falls performed by the actors. Contrast experiments are conducted with those algorithms that use RGB information directly and that classify without action prediction module. Experimental results show that our model improves the accuracy of falls recognition by utilizing body keypoints with the ability of predicting falls in advance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00275](http://arxiv.org/abs/1908.00275)

##### PDF
[http://arxiv.org/pdf/1908.00275](http://arxiv.org/pdf/1908.00275)

