---
layout: post
title: "DeepHunter: Hunting Deep Neural Network Defects via Coverage-Guided Fuzzing"
date: 2018-11-16 05:36:16
categories: arXiv_AI
tags: arXiv_AI
author: Xiaofei Xie, Lei Ma, Felix Juefei-Xu, Hongxu Chen, Minhui Xue, Bo Li, Yang Liu, Jianjun Zhao, Jianxiong Yin, Simon See
mathjax: true
---

* content
{:toc}

##### Abstract
In company with the data explosion over the past decade, deep neural network (DNN) based software has experienced unprecedented leap and is becoming the key driving force of many novel industrial applications, including many safety-critical scenarios such as autonomous driving. Despite great success achieved in various human intelligence tasks, similar to traditional software, DNNs could also exhibit incorrect behaviors caused by hidden defects causing severe accidents and losses. In this paper, we propose DeepHunter, an automated fuzz testing framework for hunting potential defects of general-purpose DNNs. DeepHunter performs metamorphic mutation to generate new semantically preserved tests, and leverages multiple plugable coverage criteria as feedback to guide the test generation from different perspectives. To be scalable towards practical-sized DNNs, DeepHunter maintains multiple tests in a batch, and prioritizes the tests selection based on active feedback. The effectiveness of DeepHunter is extensively investigated on 3 popular datasets (MNIST, CIFAR-10, ImageNet) and 7 DNNs with diverse complexities, under a large set of 6 coverage criteria as feedback. The large-scale experiments demonstrate that DeepHunter can (1) significantly boost the coverage with guidance; (2) generate useful tests to detect erroneous behaviors and facilitate the DNN model quality evaluation; (3) accurately capture potential defects during DNN quantization for platform migration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.01266](http://arxiv.org/abs/1809.01266)

##### PDF
[http://arxiv.org/pdf/1809.01266](http://arxiv.org/pdf/1809.01266)

