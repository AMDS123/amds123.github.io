---
layout: post
title: "Fully Convolutional One-Shot Object Segmentation for Industrial Robotics"
date: 2019-03-02 11:23:13
categories: arXiv_RO
tags: arXiv_RO Object_Detection Segmentation Weakly_Supervised CNN Classification Detection
author: Benjamin Schnieders, Shan Luo, Gregory Palmer, Karl Tuyls
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to identify and localize new objects robustly and effectively is vital for robotic grasping and manipulation in warehouses or smart factories. Deep convolutional neural networks (DCNNs) have achieved the state-of-the-art performance on established image datasets for object detection and segmentation. However, applying DCNNs in dynamic industrial scenarios, e.g., warehouses and autonomous production, remains a challenging problem. DCNNs quickly become ineffective when tasked with detecting objects that they have not been trained on. Given that re-training using the latest data is time consuming, DCNNs cannot meet the requirement of the Factory of the Future (FoF) regarding rapid development and production cycles. To address this problem, we propose a novel one-shot object segmentation framework, using a fully convolutional Siamese network architecture, to detect previously unknown objects based on a single prototype image. We turn to multi-task learning to reduce training time and improve classification accuracy. Furthermore, we introduce a novel approach to automatically cluster the learnt feature space representation in a weakly supervised manner. We test the proposed framework on the RoboCup@Work dataset, simulating requirements for the FoF. Results show that the trained network on average identifies 73% of previously unseen objects correctly from a single example image. Correctly identified objects are estimated to have a 87.53% successful pick-up rate. Finally, multi-task learning lowers the convergence time by up to 33%, and increases accuracy by 2.99%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00683](http://arxiv.org/abs/1903.00683)

##### PDF
[http://arxiv.org/pdf/1903.00683](http://arxiv.org/pdf/1903.00683)

