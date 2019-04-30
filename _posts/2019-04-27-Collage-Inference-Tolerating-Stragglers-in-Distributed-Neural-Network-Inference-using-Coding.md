---
layout: post
title: "Collage Inference: Tolerating Stragglers in Distributed Neural Network Inference using Coding"
date: 2019-04-27 22:56:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Inference Classification Prediction Detection
author: Krishna Giri Narra, Zhifeng Lin, Ganesh Ananthanarayanan, Salman Avestimehr, Murali Annavaram
mathjax: true
---

* content
{:toc}

##### Abstract
MLaaS (ML-as-a-Service) offerings by cloud computing platforms are becoming increasingly popular these days. Pre-trained machine learning models are deployed on the cloud to support prediction based applications and services. For achieving higher throughput, incoming requests are served by running multiple replicas of the model on different machines concurrently. Incidence of straggler nodes in distributed inference is a significant concern since it can increase inference latency, violate SLOs of the service. In this paper, we propose a novel coded inference model to deal with stragglers in distributed image classification. We propose modified single shot object detection models, Collage-CNN models, to provide necessary resilience efficiently. A Collage-CNN model takes collage images formed by combining multiple images as its input and performs multi-image classification in one shot. We generate custom training collages using images from standard image classification datasets and train the model to achieve high classification accuracy. Deploying the Collage-CNN models in the cloud, we demonstrate that the 99th percentile latency can be reduced by 1.45X to 2.46X compared to replication based approaches and without compromising prediction accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12222](http://arxiv.org/abs/1904.12222)

##### PDF
[http://arxiv.org/pdf/1904.12222](http://arxiv.org/pdf/1904.12222)

