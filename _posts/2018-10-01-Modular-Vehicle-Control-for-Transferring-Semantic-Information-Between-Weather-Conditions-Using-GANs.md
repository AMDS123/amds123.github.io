---
layout: post
title: "Modular Vehicle Control for Transferring Semantic Information Between Weather Conditions Using GANs"
date: 2018-10-01 14:01:46
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Face Prediction
author: Patrick Wenzel, Qadeer Khan, Daniel Cremers, Laura Leal-Taixé
mathjax: true
---

* content
{:toc}

##### Abstract
Even though end-to-end supervised learning has shown promising results for sensorimotor control of self-driving cars, its performance is greatly affected by the weather conditions under which it was trained, showing poor generalization to unseen conditions. In this paper, we show how knowledge can be transferred using semantic maps to new weather conditions without the need to obtain new ground truth data. To this end, we propose to divide the task of vehicle control into two independent modules: a control module which is only trained on one weather condition for which labeled steering data is available, and a perception module which is used as an interface between new weather conditions and the fixed control module. To generate the semantic data needed to train the perception module, we propose to use a generative adversarial network (GAN)-based model to retrieve the semantic information for the new conditions in an unsupervised manner. We introduce a master-servant architecture, where the master model (semantic labels available) trains the servant model (semantic labels not available). We show that our proposed method trained with ground truth data for a single weather condition is capable of achieving similar results on the task of steering angle prediction as an end-to-end model trained with ground truth data of 15 different weather conditions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.01001](https://arxiv.org/abs/1807.01001)

##### PDF
[https://arxiv.org/pdf/1807.01001](https://arxiv.org/pdf/1807.01001)

