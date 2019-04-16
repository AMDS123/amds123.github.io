---
layout: post
title: "LMNet: Real-time Multiclass Object Detection on CPU using 3D LiDAR"
date: 2018-05-18 15:41:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN CNN Quantitative Detection
author: Kazuki Minemura, Hengfui Liau, Abraham Monrroy, Shinpei Kato
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes an optimized single-stage deep convolutional neural network to detect objects in urban environments, using nothing more than point cloud data. This feature enables our method to work regardless the time of the day and the lighting conditions.The proposed network structure employs dilated convolutions to gradually increase the perceptive field as depth increases, this helps to reduce the computation time by about 30%. The network input consists of five perspective representations of the unorganized point cloud data. The network outputs an objectness map and the bounding box offset values for each point. Our experiments showed that using reflection, range, and the position on each of the three axes helped to improve the location and orientation of the output bounding box. We carried out quantitative evaluations with the help of the KITTI dataset evaluation server. It achieved the fastest processing speed among the other contenders, making it suitable for real-time applications. We implemented and tested it on a real vehicle with a Velodyne HDL-64 mounted on top of it. We achieved execution times as fast as 50 FPS using desktop GPUs, and up to 10 FPS on a single Intel Core i5 CPU. The deploy implementation is open-sourced and it can be found as a feature branch inside the autonomous driving framework Autoware. Code is available at: this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.04902](https://arxiv.org/abs/1805.04902)

##### PDF
[https://arxiv.org/pdf/1805.04902](https://arxiv.org/pdf/1805.04902)

