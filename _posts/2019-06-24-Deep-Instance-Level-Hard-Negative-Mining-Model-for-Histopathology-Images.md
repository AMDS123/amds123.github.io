---
layout: post
title: "Deep Instance-Level Hard Negative Mining Model for Histopathology Images"
date: 2019-06-24 01:00:05
categories: arXiv_AI
tags: arXiv_AI Attention CNN Classification Prediction
author: Meng Li, Lin Wu, Arnold Wiliem, Kun Zhao, Teng Zhang, Brian C. Lovell
mathjax: true
---

* content
{:toc}

##### Abstract
Histopathology image analysis can be considered as a Multiple instance learning (MIL) problem, where the whole slide histopathology image (WSI) is regarded as a bag of instances i.e, patches) and the task is to predict a single class label to the WSI. However, in many real-life applications such as computational pathology, discovering the key instances that trigger the bag label is of great interest because it provides reasons for the decision made by the system. In this paper, we propose a deep convolutional neural network (CNN) model that addresses the primary task of a bag classification on a WSI and also learns to identify the response of each instance to provide interpretable results to the final prediction. We incorporate the attention mechanism into the proposed model to operate the transformation of instances and learn attention weights to allow us to find key patches. To perform a balanced training, we introduce adaptive weighing in each training bag to explicitly adjust the weight distribution in order to concentrate more on the contribution of hard samples. Based on the learned attention weights, we further develop a solution to boost the classification performance by generating the bags with hard negative instances. We conduct extensive experiments on colon and breast cancer histopathology data and show that our framework achieves state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09681](http://arxiv.org/abs/1906.09681)

##### PDF
[http://arxiv.org/pdf/1906.09681](http://arxiv.org/pdf/1906.09681)

