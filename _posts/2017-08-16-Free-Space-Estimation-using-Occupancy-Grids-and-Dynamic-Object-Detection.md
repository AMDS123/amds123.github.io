---
layout: post
title: "Free Space Estimation using Occupancy Grids and Dynamic Object Detection"
date: 2017-08-16 17:28:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Tracking Detection
author: Raghavender Sahdev
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present an approach to estimate Free Space from a Stereo image pair using stochastic occupancy grids. We do this in the domain of autonomous driving on the famous benchmark dataset KITTI. Later based on the generated occupancy grid we match 2 image sequences to compute the top view representation of the map. We do this to map the environment. We compute a transformation between the occupancy grids of two successive images and use it to compute the top view map. Two issues need to be addressed for mapping are discussed - computing a map and dealing with dynamic objects for computing the map. Dynamic Objects are detected in successive images based on an idea similar to tracking of foreground objects from the background objects based on motion flow. A novel RANSAC based segmentation approach has been proposed here to address this issue.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.04989](https://arxiv.org/abs/1708.04989)

##### PDF
[https://arxiv.org/pdf/1708.04989](https://arxiv.org/pdf/1708.04989)

