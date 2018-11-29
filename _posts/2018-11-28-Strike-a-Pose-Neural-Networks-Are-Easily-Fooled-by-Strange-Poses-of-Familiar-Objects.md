---
layout: post
title: "Strike a Pose: Neural Networks Are Easily Fooled by Strange Poses of Familiar Objects"
date: 2018-11-28 13:39:27
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Michael A. Alcorn, Qi Li, Zhitao Gong, Chengfei Wang, Long Mai, Wei-Shinn Ku, Anh Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Despite excellent performance on stationary test sets, deep neural networks (DNNs) can fail to generalize to out-of-distribution (OoD) inputs, including natural, non-adversarial ones, which are common in real-world settings. In this paper, we present a framework for discovering DNN failures that harnesses 3D renderers and 3D models. That is, we estimate the parameters of a 3D renderer that cause a target DNN to misbehave in response to the rendered image. Using our framework and a self-assembled dataset of 3D objects, we investigate the vulnerability of DNNs to OoD poses of well-known objects in ImageNet. For objects that are readily recognized by DNNs in their canonical poses, DNNs incorrectly classify 97% of their pose space. In addition, DNNs are highly sensitive to slight pose perturbations. Importantly, adversarial poses transfer across models and datasets. We find that 99.9% and 99.4% of the poses misclassified by Inception-v3 also transfer to the AlexNet and ResNet-50 image classifiers trained on the same ImageNet dataset, respectively, and 75.5% transfer to the YOLOv3 object detector trained on MS COCO.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11553](http://arxiv.org/abs/1811.11553)

##### PDF
[http://arxiv.org/pdf/1811.11553](http://arxiv.org/pdf/1811.11553)

