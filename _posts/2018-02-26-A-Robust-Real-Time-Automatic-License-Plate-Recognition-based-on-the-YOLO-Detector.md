---
layout: post
title: "A Robust Real-Time Automatic License Plate Recognition based on the YOLO Detector"
date: 2018-02-26 19:31:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection Recognition
author: Rayson Laroca, Evair Severo, Luiz A. Zanlorensi, Luiz S. Oliveira, Gabriel R. Gonçalves, William R. Schwartz, David Menotti
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic License Plate Recognition (ALPR) has been a frequent topic of research due to many practical applications. However, many of the current solutions are still not robust in real-world situations, commonly depending on many constraints. This paper presents a robust and efficient ALPR system based on the state-of-the-art YOLO object detection. The Convolutional Neural Networks (CNNs) are trained and fine-tuned for each ALPR stage so that they are robust under different conditions (e.g., variations in camera, lighting, and background). Specially for character segmentation and recognition, we design a two-stage approach employing simple data augmentation tricks such as inverted License Plates (LPs) and flipped characters. The resulting ALPR approach achieved impressive results in two datasets. First, in the SSIG dataset, composed of 2,000 frames from 101 vehicle videos, our system achieved a recognition rate of 93.53% and 47 Frames Per Second (FPS), performing better than both Sighthound and OpenALPR commercial systems (89.80% and 93.03%, respectively) and considerably outperforming previous results (81.80%). Second, targeting a more realistic scenario, we introduce a larger public dataset, called UFPR-ALPR dataset, designed to ALPR. This dataset contains 150 videos and 4,500 frames captured when both camera and vehicles are moving and also contains different types of vehicles (cars, motorcycles, buses and trucks). In our proposed dataset, the trial versions of commercial systems achieved recognition rates below 70%. On the other hand, our system performed better, with recognition rate of 78.33% and 35 FPS.

##### Abstract (translated by Google)
由于许多实际应用，自动车牌识别（ALPR）一直是研究的一个常见话题。然而，目前许多解决方案在现实世界中仍然不健壮，通常取决于许多限制因素。本文提出了一种基于最先进的YOLO物体检测的强大而高效的ALPR系统。卷积神经网络（CNN）针对每个ALPR阶段进行训练和微调，以便它们在不同条件下（例如，相机，照明和背景中的变化）具有鲁棒性。特别是对于字符分割和识别，我们设计了一个两阶段方法，采用简单的数据增强技巧，例如倒立牌照（LP）和翻转字符。由此产生的ALPR方法在两个数据集中取得了可观的成果。首先，SSIG数据集由来自101个车辆视频的2000帧组成，其识别率达到93.53％和47帧每秒（FPS），比Sighthound和OpenALPR商业系统（89.80％和93.03％分别）和显着优于以前的结果（81.80％）。其次，针对更现实的情况，我们引入了一个更大的公共数据集，称为UFPR-ALPR数据集，专为ALPR设计。这个数据集包含150个视频和4,500帧，当摄像头和车辆移动时，还包含不同类型的车辆（汽车，摩托车，公共汽车和卡车）。在我们提出的数据集中，商业系统的试用版达到了70％以下的识别率。另一方面，我们的系统表现更好，识别率为78.33％和35 FPS。

##### URL
[https://arxiv.org/abs/1802.09567](https://arxiv.org/abs/1802.09567)

##### PDF
[https://arxiv.org/pdf/1802.09567](https://arxiv.org/pdf/1802.09567)

