---
layout: post
title: "A fast online cascaded regression algorithm for face alignment"
date: 2019-05-10 08:37:33
categories: arXiv_CV
tags: arXiv_CV Knowledge Face
author: Lin Feng, Caifeng Liu, Shenglan Liu, Huibing Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional face alignment based on machine learning usually tracks the localizations of facial landmarks employing a static model trained offline where all of the training data is available in advance. When new training samples arrive, the static model must be retrained from scratch, which is excessively time-consuming and memory-consuming. In many real-time applications, the training data is obtained one by one or batch by batch. It results in that the static model limits its performance on sequential images with extensive variations. Therefore, the most critical and challenging aspect in this field is dynamically updating the tracker's models to enhance predictive and generalization capabilities continuously. In order to address this question, we develop a fast and accurate online learning algorithm for face alignment. Particularly, we incorporate on-line sequential extreme learning machine into a parallel cascaded regression framework, coined incremental cascade regression(ICR). To the best of our knowledge, this is the first incremental cascaded framework with the non-linear regressor. One main advantage of ICR is that the tracker model can be fast updated in an incremental way without the entire retraining process when a new input is incoming. Experimental results demonstrate that the proposed ICR is more accurate and efficient on still or sequential images compared with the recent state-of-the-art cascade approaches. Furthermore, the incremental learning proposed in this paper can update the trained model in real time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04010](http://arxiv.org/abs/1905.04010)

##### PDF
[http://arxiv.org/pdf/1905.04010](http://arxiv.org/pdf/1905.04010)

