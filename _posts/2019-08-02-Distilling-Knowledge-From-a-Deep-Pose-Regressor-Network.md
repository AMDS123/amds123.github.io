---
layout: post
title: "Distilling Knowledge From a Deep Pose Regressor Network"
date: 2019-08-02 13:48:31
categories: arXiv_CV
tags: arXiv_CV Knowledge Prediction
author: Muhamad Risqi U. Saputra, Pedro P. B. de Gusmao, Yasin Almalioglu, Andrew Markham, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel method to distill knowledge from a deep pose regressor network for efficient Visual Odometry (VO). Standard distillation relies on "dark knowledge" for successful knowledge transfer. As this knowledge is not available in pose regression and the teacher prediction is not always accurate, we propose to emphasize the knowledge transfer only when we trust the teacher. We achieve this by using teacher loss as a confidence score which places variable relative importance on the teacher prediction. We inject this confidence score to the main training task via Attentive Imitation Loss (AIL) and when learning the intermediate representation of the teacher through Attentive Hint Training (AHT) approach. To the best of our knowledge, this is the first work which successfully distill the knowledge from a deep pose regression network. Our evaluation on the KITTI and Malaga dataset shows that we can keep the student prediction close to the teacher with up to 92.95% parameter reduction and 2.12x faster in computation time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00858](http://arxiv.org/abs/1908.00858)

##### PDF
[http://arxiv.org/pdf/1908.00858](http://arxiv.org/pdf/1908.00858)

