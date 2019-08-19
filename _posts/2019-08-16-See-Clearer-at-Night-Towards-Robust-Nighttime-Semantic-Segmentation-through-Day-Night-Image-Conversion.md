---
layout: post
title: "See Clearer at Night: Towards Robust Nighttime Semantic Segmentation through Day-Night Image Conversion"
date: 2019-08-16 06:56:55
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Face Semantic_Segmentation Quantitative
author: Lei Sun, Kaiwei Wang, Kailun Yang, Kaite Xiang
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, semantic segmentation shows remarkable efficiency and reliability in standard scenarios such as daytime scenes with favorable illumination conditions. However, in face of adverse conditions such as the nighttime, semantic segmentation loses its accuracy significantly. One of the main causes of the problem is the lack of sufficient annotated segmentation datasets of nighttime scenes. In this paper, we propose a framework to alleviate the accuracy decline when semantic segmentation is taken to adverse conditions by using Generative Adversarial Networks (GANs). To bridge the daytime and nighttime image domains, we made key observation that compared to datasets in adverse conditions, there are considerable amount of segmentation datasets in standard conditions such as BDD and our collected ZJU datasets. Our GAN-based nighttime semantic segmentation framework includes two methods. In the first method, GANs were used to translate nighttime images to the daytime, thus semantic segmentation can be performed using robust models already trained on daytime datasets. In another method, we use GANs to translate different ratio of daytime images in the dataset to the nighttime but still with their labels. In this sense, synthetic nighttime segmentation datasets can be generated to yield models prepared to operate at nighttime conditions robustly. In our experiment, the later method significantly boosts the performance at the nighttime evidenced by quantitative results using Intersection over Union (IoU) and Pixel Accuracy (Acc). We show that the performance varies with respect to the proportion of synthetic nighttime images in the dataset, where the sweet spot corresponds to most robust performance across the day and night.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05868](https://arxiv.org/abs/1908.05868)

##### PDF
[https://arxiv.org/pdf/1908.05868](https://arxiv.org/pdf/1908.05868)

