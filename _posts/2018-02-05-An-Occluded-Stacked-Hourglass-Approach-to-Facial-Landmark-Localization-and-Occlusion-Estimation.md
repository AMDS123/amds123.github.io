---
layout: post
title: "An Occluded Stacked Hourglass Approach to Facial Landmark Localization and Occlusion Estimation"
date: 2018-02-05 19:17:52
categories: arXiv_CV
tags: arXiv_CV Attention Face Quantitative Detection Face_Detection
author: Kevan Yuen, Mohan M. Trivedi
mathjax: true
---

* content
{:toc}

##### Abstract
A key step to driver safety is to observe the driver's activities with the face being a key step in this process to extracting information such as head pose, blink rate, yawns, talking to passenger which can then help derive higher level information such as distraction, drowsiness, intent, and where they are looking. In the context of driving safety, it is important for the system perform robust estimation under harsh lighting and occlusion but also be able to detect when the occlusion occurs so that information predicted from occluded parts of the face can be taken into account properly. This paper introduces the Occluded Stacked Hourglass, based on the work of original Stacked Hourglass network for body pose joint estimation, which is retrained to process a detected face window and output 68 occlusion heat maps, each corresponding to a facial landmark. Landmark location, occlusion levels and a refined face detection score, to reject false positives, are extracted from these heat maps. Using the facial landmark locations, features such as head pose and eye/mouth openness can be extracted to derive driver attention and activity. The system is evaluated for face detection, head pose, and occlusion estimation on various datasets in the wild, both quantitatively and qualitatively, and shows state-of-the-art results.

##### Abstract (translated by Google)
驾驶员安全的一个关键步骤是观察驾驶员的活动，在这个过程中，人脸是提取头部姿态，眨眼率，打哈欠，打电话给乘客等信息的关键步骤，从而有助于获得更高水平的信息，如分心，嗜睡，意图，他们在哪里看。在驾驶安全的情况下，系统在强烈的照明和遮挡下执行鲁棒性估计是重要的，但是也能够检测何时发生遮挡，使得从遮挡的脸部预测的信息能够被适当地考虑。本文介绍了Occluded Stacked Hourglass，基于原有Stacked Hourglass网络对身体姿态联合估计的工作，对训练后的人脸进行重新训练，输出68个遮挡热图，每个遮挡热图对应一个面部标志。从这些热图提取地标位置，遮挡等级和精确的人脸检测分数以拒绝误报。使用面部地标位置，可以提取诸如头部姿势和眼睛/嘴巴张开等特征以获得驾驶者的注意力和活动。该系统在数量和质量上对各种数据集中的人脸检测，头部姿态和遮挡估计进行评估，并显示最新的结果。

##### URL
[https://arxiv.org/abs/1802.02137](https://arxiv.org/abs/1802.02137)

##### PDF
[https://arxiv.org/pdf/1802.02137](https://arxiv.org/pdf/1802.02137)

