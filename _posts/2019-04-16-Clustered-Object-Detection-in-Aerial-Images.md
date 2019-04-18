---
layout: post
title: "Clustered Object Detection in Aerial Images"
date: 2019-04-16 23:01:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Drone Detection
author: Fan Yang, Heng Fan, Peng Chu, Erik Blasch, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting objects in aerial images is challenging for at least two reasons: (1) target objects like pedestrians are very small in terms of pixels, making them hard to be distinguished from surrounding background; and (2) targets are in general very sparsely and nonuniformly distributed, making the detection very inefficient. In this paper we address both issues inspired by the observation that these targets are often clustered. In particular, we propose a Clustered Detection (ClusDet) network that unifies object cluster and detection in an end-to-end framework. The key components in ClusDet include a cluster proposal sub-network (CPNet), a scale estimation sub-network (ScaleNet), and a dedicated detection network (DetecNet). Given an input image, CPNet produces (object) cluster regions and ScaleNet estimates object scales for these regions. Then, each scale-normalized cluster region and their features are fed into DetecNet for object detection. Compared with previous solutions, ClusDet has several advantages: (1) it greatly reduces the number of blocks for final object detection and hence achieves high running time efficiency, (2) the cluster-based scale estimation is more accurate than previously used single-object based ones, hence effectively improves the detection for small objects, and (3) the final DetecNet is dedicated for clustered regions and implicitly models the prior context information so as to boost detection accuracy. The proposed method is tested on three representative aerial image datasets including VisDrone, UAVDT and DOTA. In all the experiments, ClusDet achieves promising performance in both efficiency and accuracy, in comparison with state-of-the-art detectors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08008](http://arxiv.org/abs/1904.08008)

##### PDF
[http://arxiv.org/pdf/1904.08008](http://arxiv.org/pdf/1904.08008)

