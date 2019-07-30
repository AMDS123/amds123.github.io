---
layout: post
title: "ROAM: Recurrently Optimizing Tracking Model"
date: 2019-07-28 03:50:05
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization
author: Tianyu Yang, Pengfei Xu, Runbo Hu, Hua Chai, Antoni B. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Online updating a tracking model to adapt to object appearance variations is challenging. For SGD-based model optimization, using a large learning rate may help to converge the model faster but has the risk of letting the loss wander wildly. Thus traditional optimization methods usually choose a relatively small learning rate and iterate for more steps to converge the model, which is time-consuming. In this paper, we propose to offline train a recurrent neural optimizer to predict an adaptive learning rate for model updating in a meta-learning setting, which can converge the model in a few gradient steps. This substantially improves the convergence speed of updating the tracking model, while achieving better performance. Moreover, we also propose a simple yet effective training trick called Random Filter Scaling to prevent overfitting, which boosts the performance greatly. Finally, we extensively evaluate our tracker, ROAM, on the OTB, VOT, GOT-10K, TrackingNet and LaSOT benchmark and our method performs favorably against state-of-the-art algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12006](http://arxiv.org/abs/1907.12006)

##### PDF
[http://arxiv.org/pdf/1907.12006](http://arxiv.org/pdf/1907.12006)

