---
layout: post
title: "TensorFlow Estimators: Managing Simplicity vs. Flexibility in High-Level Machine Learning Frameworks"
date: 2017-08-08 20:06:28
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Heng-Tze Cheng, Zakaria Haque, Lichan Hong, Mustafa Ispir, Clemens Mewald, Illia Polosukhin, Georgios Roumpos, D Sculley, Jamie Smith, David Soergel, Yuan Tang, Philipp Tucker, Martin Wicke, Cassandra Xia, Jianwei Xie
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for specifying, training, evaluating, and deploying machine learning models. Our focus is on simplifying cutting edge machine learning for practitioners in order to bring such technologies into production. Recognizing the fast evolution of the field of deep learning, we make no attempt to capture the design space of all possible model architectures in a domain- specific language (DSL) or similar configuration language. We allow users to write code to define their models, but provide abstractions that guide develop- ers to write models in ways conducive to productionization. We also provide a unifying Estimator interface, making it possible to write downstream infrastructure (e.g. distributed training, hyperparameter tuning) independent of the model implementation. We balance the competing demands for flexibility and simplicity by offering APIs at different levels of abstraction, making common model architectures available out of the box, while providing a library of utilities designed to speed up experimentation with model architectures. To make out of the box models flexible and usable across a wide range of problems, these canned Estimators are parameterized not only over traditional hyperparameters, but also using feature columns, a declarative specification describing how to interpret input data. We discuss our experience in using this framework in re- search and production environments, and show the impact on code health, maintainability, and development speed.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.02637](https://arxiv.org/abs/1708.02637)

##### PDF
[https://arxiv.org/pdf/1708.02637](https://arxiv.org/pdf/1708.02637)

