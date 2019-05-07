---
layout: post
title: "Energy-Efficient Object Detection using Semantic Decomposition"
date: 2016-09-20 14:38:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Priyadarshini Panda, Swagath Venkataramani, Abhronil Sengupta, Anand Raghunathan, Kaushik Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Machine-learning algorithms offer immense possibilities in the development of several cognitive applications. In fact, large scale machine-learning classifiers now represent the state-of-the-art in a wide range of object detection/classification problems. However, the network complexities of large-scale classifiers present them as one of the most challenging and energy intensive workloads across the computing spectrum. In this paper, we present a new approach to optimize energy efficiency of object detection tasks using semantic decomposition to build a hierarchical classification framework. We observe that certain semantic information like color/texture are common across various images in real-world datasets for object detection applications. We exploit these common semantic features to distinguish the objects of interest from the remaining inputs (non-objects of interest) in a dataset at a lower computational effort. We propose a 2-stage hierarchical classification framework, with increasing levels of complexity, wherein the first stage is trained to recognize the broad representative semantic features relevant to the object of interest. The first stage rejects the input instances that do not have the representative features and passes only the relevant instances to the second stage. Our methodology thus allows us to reject certain information at lower complexity and utilize the full computational effort of a network only on a smaller fraction of inputs to perform detection. We use color and texture as distinctive traits to carry out several experiments for object detection. Our experiments on the Caltech101/CIFAR10 dataset show that the proposed method yields 1.93x/1.46x improvement in average energy, respectively, over the traditional single classifier model.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1509.08970](https://arxiv.org/abs/1509.08970)

##### PDF
[https://arxiv.org/pdf/1509.08970](https://arxiv.org/pdf/1509.08970)

