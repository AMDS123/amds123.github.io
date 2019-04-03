---
layout: post
title: "C2AE: Class Conditioned Auto-Encoder for Open-set Recognition"
date: 2019-04-02 03:47:39
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Recognition
author: Poojan Oza, Vishal M Patel
mathjax: true
---

* content
{:toc}

##### Abstract
Models trained for classification often assume that all testing classes are known while training. As a result, when presented with an unknown class during testing, such closed-set assumption forces the model to classify it as one of the known classes. However, in a real world scenario, classification models are likely to encounter such examples. Hence, identifying those examples as unknown becomes critical to model performance. A potential solution to overcome this problem lies in a class of learning problems known as open-set recognition. It refers to the problem of identifying the unknown classes during testing, while maintaining performance on the known classes. In this paper, we propose an open-set recognition algorithm using class conditioned auto-encoders with novel training and testing methodology. In contrast to previous methods, training procedure is divided in two sub-tasks, 1. closed-set classification and, 2. open-set identification (i.e. identifying a class as known or unknown). Encoder learns the first task following the closed-set classification training pipeline, whereas decoder learns the second task by reconstructing conditioned on class identity. Furthermore, we model reconstruction errors using the Extreme Value Theory of statistical modeling to find the threshold for identifying known/unknown class samples. Experiments performed on multiple image classification datasets show proposed method performs significantly better than state of the art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01198](http://arxiv.org/abs/1904.01198)

##### PDF
[http://arxiv.org/pdf/1904.01198](http://arxiv.org/pdf/1904.01198)

