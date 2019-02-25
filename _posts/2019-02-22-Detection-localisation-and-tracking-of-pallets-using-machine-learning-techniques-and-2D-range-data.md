---
layout: post
title: "Detection, localisation and tracking of pallets using machine learning techniques and 2D range data"
date: 2019-02-22 12:03:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Detection
author: Ihab S. Mohamed, Alessio Capitanelli, Fulvio Mastrogiovanni, Stefano Rovetta, Renato Zaccaria
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of autonomous transportation in industrial scenarios is receiving a renewed interest due to the way it can revolutionise internal logistics, especially in unstructured environments. This paper presents a novel architecture allowing a robot to detect, localise, and track (possibly multiple) pallets using machine learning techniques based on an on-board 2D laser rangefinder only. The architecture is composed of two main components: the first stage is a pallet detector employing a Faster Region-based Convolutional Neural Network (Faster R-CNN) detector cascaded with a CNN-based classifier; the second stage is a Kalman filter for localising and tracking detected pallets, which we also use to defer commitment to a pallet detected in the first stage until sufficient confidence has been acquired via a sequential data acquisition process. For fine-tuning the CNNs, the architecture has been systematically evaluated using a real-world dataset containing 340 labeled 2D scans, which have been made freely available in an online repository. Detection performance has been assessed on the basis of the average accuracy over k-fold cross-validation, and it scored 99.58% in our tests. Concerning pallet localisation and tracking, experiments have been performed in a scenario where the robot is approaching the pallet to fork. Although data have been originally acquired by considering only one pallet as per specification of the use case we consider, artificial data have been generated as well to mimic the presence of multiple pallets in the robot workspace. Our experimental results confirm that the system is capable of identifying, localising and tracking pallets with a high success rate while being robust to false positives.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.11254](http://arxiv.org/abs/1803.11254)

##### PDF
[http://arxiv.org/pdf/1803.11254](http://arxiv.org/pdf/1803.11254)

