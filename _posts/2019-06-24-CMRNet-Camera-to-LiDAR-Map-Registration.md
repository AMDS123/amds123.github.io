---
layout: post
title: "CMRNet: Camera to LiDAR-Map Registration"
date: 2019-06-24 17:53:28
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking CNN
author: Daniele Cattaneo, Matteo Vaghi, Augusto Luis Ballardini, Simone Fontana, Domenico Giorgio Sorrenti, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present CMRNet, a realtime approach based on a Convolutional Neural Network to localize an RGB image of a scene in a map built from LiDAR data. Our network is not trained on the working area, i.e. CMRNet does not learn the map. Instead it learns to match an image to the map. We validate our approach on the KITTI dataset, processing each frame independently without any tracking procedure. CMRNet achieves 0.26m and 1.05deg median localization accuracy on the sequence 00 of the odometry dataset, starting from a rough pose estimate displaced up to 3.5m and 17deg. To the best of our knowledge this is the first CNN-based approach that learns to match images from a monocular camera to a given, preexisting 3D LiDAR-map.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10109](http://arxiv.org/abs/1906.10109)

##### PDF
[http://arxiv.org/pdf/1906.10109](http://arxiv.org/pdf/1906.10109)

