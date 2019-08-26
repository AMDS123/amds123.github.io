---
layout: post
title: "MTCNET: Multi-task Learning Paradigm for Crowd Count Estimation"
date: 2019-08-23 03:30:53
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Abhay Kumar, Nishant Jain, Suraj Tripathi, Chirag Singh, Kamal Krishna
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Multi-Task Learning (MTL) paradigm based deep neural network architecture, called MTCNet (Multi-Task Crowd Network) for crowd density and count estimation. Crowd count estimation is challenging due to the non-uniform scale variations and the arbitrary perspective of an individual image. The proposed model has two related tasks, with Crowd Density Estimation as the main task and Crowd-Count Group Classification as the auxiliary task. The auxiliary task helps in capturing the relevant scale-related information to improve the performance of the main task. The main task model comprises two blocks: VGG-16 front-end for feature extraction and a dilated Convolutional Neural Network for density map generation. The auxiliary task model shares the same front-end as the main task, followed by a CNN classifier. Our proposed network achieves 5.8% and 14.9% lower Mean Absolute Error (MAE) than the state-of-the-art methods on ShanghaiTech dataset without using any data augmentation. Our model also outperforms with 10.5% lower MAE on UCF_CC_50 dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08652](http://arxiv.org/abs/1908.08652)

##### PDF
[http://arxiv.org/pdf/1908.08652](http://arxiv.org/pdf/1908.08652)

