---
layout: post
title: "ODN: Opening the Deep Network for Open-set Action Recognition"
date: 2019-01-23 07:49:31
categories: arXiv_CV
tags: arXiv_CV Knowledge Action_Recognition Classification Recognition
author: Yu Shu, Yemin Shi, Yaowei Wang, Yixiong Zou, Qingsheng Yuan, Yonghong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, the performance of action recognition has been significantly improved with the help of deep neural networks. Most of the existing action recognition works hold the \textit{closed-set} assumption that all action categories are known beforehand while deep networks can be well trained for these categories. However, action recognition in the real world is essentially an \textit{open-set} problem, namely, it is impossible to know all action categories beforehand and consequently infeasible to prepare sufficient training samples for those emerging categories. In this case, applying closed-set recognition methods will definitely lead to unseen-category errors. To address this challenge, we propose the Open Deep Network (ODN) for the open-set action recognition task. Technologically, ODN detects new categories by applying a multi-class triplet thresholding method, and then dynamically reconstructs the classification layer and "opens" the deep network by adding predictors for new categories continually. In order to transfer the learned knowledge to the new category, two novel methods, Emphasis Initialization and Allometry Training, are adopted to initialize and incrementally train the new predictor so that only few samples are needed to fine-tune the model. Extensive experiments show that ODN can effectively detect and recognize new categories with little human intervention, thus applicable to the open-set action recognition tasks in the real world. Moreover, ODN can even achieve comparable performance to some closed-set methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07757](http://arxiv.org/abs/1901.07757)

##### PDF
[http://arxiv.org/pdf/1901.07757](http://arxiv.org/pdf/1901.07757)

