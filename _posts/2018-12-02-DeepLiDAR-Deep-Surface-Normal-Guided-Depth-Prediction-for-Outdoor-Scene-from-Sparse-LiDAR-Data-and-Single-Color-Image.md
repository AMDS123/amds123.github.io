---
layout: post
title: "DeepLiDAR: Deep Surface Normal Guided Depth Prediction for Outdoor Scene from Sparse LiDAR Data and Single Color Image"
date: 2018-12-02 23:36:22
categories: arXiv_CV
tags: arXiv_CV Sparse Attention Face Deep_Learning Prediction
author: Jiaxiong Qiu, Zhaopeng Cui, Yinda Zhang, Xingdi Zhang, Shuaicheng Liu, Bing Zeng, Marc Pollefeys
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a deep learning architecture that produces accurate dense depth for the outdoor scene from a single color image and a sparse depth. Inspired by the indoor depth completion, our network estimates surface normals as the intermediate representation to produce dense depth, and can be trained end-to-end. With a modified encoder-decoder structure, our network effectively fuses the dense color image and the sparse LiDAR depth. To address outdoor specific challenges, our network predicts a confidence mask to handle mixed LiDAR signals near foreground boundaries due to occlusion, and combines estimates from the color image and surface normals with learned attention maps to improve the depth accuracy especially for distant areas. Extensive experiments demonstrate that our model improves upon the state-of-the-art performance on KITTI depth completion benchmark. Ablation study shows the positive impact of each model components to the final performance, and comprehensive analysis shows that our model generalizes well to the input with higher sparsity or from indoor scenes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00488](http://arxiv.org/abs/1812.00488)

##### PDF
[http://arxiv.org/pdf/1812.00488](http://arxiv.org/pdf/1812.00488)

