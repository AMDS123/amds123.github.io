---
layout: post
title: "Face Detection, Bounding Box Aggregation and Pose Estimation for Robust Facial Landmark Localisation in the Wild"
date: 2017-06-01 10:28:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Pose_Estimation Detection Face_Detection
author: Zhen-Hua Feng, Josef Kittler, Muhammad Awais, Patrik Huber, Xiao-Jun Wu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for robust face detection and landmark localisation of faces in the wild, which has been evaluated as part of `the 2nd Facial Landmark Localisation Competition'. The framework has four stages: face detection, bounding box aggregation, pose estimation and landmark localisation. To achieve a high detection rate, we use two publicly available CNN-based face detectors and two proprietary detectors. We aggregate the detected face bounding boxes of each input image to reduce false positives and improve face detection accuracy. A cascaded shape regressor, trained using faces with a variety of pose variations, is then employed for pose estimation and image pre-processing. Last, we train the final cascaded shape regressor for fine-grained landmark localisation, using a large number of training samples with limited pose variations. The experimental results obtained on the 300W and Menpo benchmarks demonstrate the superiority of our framework over state-of-the-art methods.

##### Abstract (translated by Google)
我们提出了一个强大的人脸检测框架和地标在野外的本地化，这已被评估为“第二次面部标志本地化竞争”的一部分。该框架有四个阶段：人脸检测，包围盒聚合，姿态估计和地标定位。为了实现高检测率，我们使用了两个公开可用的基于CNN的人脸检测器和两个专有的检测器。我们将检测到的每个输入图像的边界框进行聚合，以减少误报，提高人脸检测的准确性。然后采用级联形状回归器，使用具有各种姿态变化的面部进行训练，以进行姿态估计和图像预处理。最后，我们训练最终的级联形状回归器，用于细粒度的地标定位，使用大量的姿势变化有限的训练样本。在300W和Menpo基准上获得的实验结果证明了我们的框架优于最先进的方法。

##### URL
[https://arxiv.org/abs/1705.02402](https://arxiv.org/abs/1705.02402)

##### PDF
[https://arxiv.org/pdf/1705.02402](https://arxiv.org/pdf/1705.02402)

