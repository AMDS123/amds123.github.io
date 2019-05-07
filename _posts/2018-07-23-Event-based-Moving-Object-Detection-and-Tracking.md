---
layout: post
title: "Event-based Moving Object Detection and Tracking"
date: 2018-07-23 02:25:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Detection
author: Anton Mitrokhin, Cornelia Fermuller, Chethan Parameshwara, Yiannis Aloimonos
mathjax: true
---

* content
{:toc}

##### Abstract
Event-based vision sensors, such as the Dynamic Vision Sensor (DVS), are ideally suited for real-time motion analysis. The unique properties encompassed in the readings of such sensors provide high temporal resolution, superior sensitivity to light and low latency. These properties provide the grounds to estimate motion extremely reliably in the most sophisticated scenarios but they come at a price - modern event-based vision sensors have extremely low resolution and produce a lot of noise. Moreover, the asynchronous nature of the event stream calls for novel algorithms. This paper presents a new, efficient approach to object tracking with asynchronous cameras. We present a novel event stream representation which enables us to utilize information about the dynamic (temporal) component of the event stream, and not only the spatial component, at every moment of time. This is done by approximating the 3D geometry of the event stream with a parametric model; as a result, the algorithm is capable of producing the motion-compensated event stream (effectively approximating egomotion), and without using any form of external sensors in extremely low-light and noisy conditions without any form of feature tracking or explicit optical flow computation. We demonstrate our framework on the task of independent motion detection and tracking, where we use the temporal model inconsistencies to locate differently moving objects in challenging situations of very fast motion.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.04523](https://arxiv.org/abs/1803.04523)

##### PDF
[https://arxiv.org/pdf/1803.04523](https://arxiv.org/pdf/1803.04523)

