---
layout: post
title: "LCC: Learning to Customize and Combine Neural Networks for Few-Shot Learning"
date: 2019-04-17 20:02:24
categories: arXiv_CV
tags: arXiv_CV Regularization Recognition
author: Yaoyao Liu, Qianru Sun, An-An Liu, Yuting Su, Bernt Schiele, Tat-Seng Chua
mathjax: true
---

* content
{:toc}

##### Abstract
Meta-learning has been shown to be an effective strategy for few-shot learning. The key idea is to leverage a large number of similar few-shot tasks in order to meta-learn how to best initiate a (single) base-learner for novel few-shot tasks. While meta-learning how to initialize a base-learner has shown promising results, it is well known that hyperparameter settings such as the learning rate and the weighting of the regularization term are important to achieve best performance. We thus propose to also meta-learn these hyperparameters and in fact learn a time- and layer-varying scheme for learning a base-learner on novel tasks. Additionally, we propose to learn not only a single base-learner but an ensemble of several base-learners to obtain more robust results. While ensembles of learners have shown to improve performance in various settings, this is challenging for few-shot learning tasks due to the limited number of training samples. Therefore, our approach also aims to meta-learn how to effectively combine several base-learners. We conduct extensive experiments and report top performance for five-class few-shot recognition tasks on two challenging benchmarks: miniImageNet and Fewshot-CIFAR100 (FC100).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08479](http://arxiv.org/abs/1904.08479)

##### PDF
[http://arxiv.org/pdf/1904.08479](http://arxiv.org/pdf/1904.08479)

