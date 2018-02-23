---
layout: post
title: "Stereo obstacle detection for unmanned surface vehicles by IMU-assisted semantic segmentation"
date: 2018-02-22 09:52:43
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation Optimization Detection
author: Borja Bovcon, Rok Mandeljc, Janez Per&#x161;, Matej Kristan
mathjax: true
---

* content
{:toc}

##### Abstract
A new obstacle detection algorithm for unmanned surface vehicles (USVs) is presented. A state-of-the-art graphical model for semantic segmentation is extended to incorporate boat pitch and roll measurements from the on-board inertial measurement unit (IMU), and a stereo verification algorithm that consolidates tentative detections obtained from the segmentation is proposed. The IMU readings are used to estimate the location of horizon line in the image, which automatically adjusts the priors in the probabilistic semantic segmentation model. We derive the equations for projecting the horizon into images, propose an efficient optimization algorithm for the extended graphical model, and offer a practical IMU-camera-USV calibration procedure. Using an USV equipped with multiple synchronized sensors, we captured a new challenging multi-modal dataset, and annotated its images with water edge and obstacles. Experimental results show that the proposed algorithm significantly outperforms the state of the art, with nearly 30% improvement in water-edge detection accuracy, an over 21% reduction of false positive rate, an almost 60% reduction of false negative rate, and an over 65% increase of true positive rate, while its Matlab implementation runs in real-time.

##### Abstract (translated by Google)
提出了一种新型的无人地面车辆（USVs）障碍物检测算法。扩展了用于语义分割的最新图形模型，以结合船载惯性测量单元（IMU）的船俯仰和侧倾测量，并提出了一种立体验证算法，用于合并从分割中获得的暂时性检测。 IMU读数用于估计图像中水平线的位置，从而自动调整概率语义分割模型中的先验。我们推导了将视界投影到图像中的方程，为扩展图形模型提出了一种有效的优化算法，并提供了一种实用的IMU相机USV校准程序。使用配备多个同步传感器的USV，我们捕获了一个新的具有挑战性的多模态数据集，并用水边和障碍物对其图像进行注释。实验结果表明，该算法明显优于现有技术，水边检测精度提高近30％，假阳性率降低21％以上，假阴性率降低近60％，超过真正的阳性率提高了65％，而Matlab的实现则实时运行。

##### URL
[http://arxiv.org/abs/1802.07956](http://arxiv.org/abs/1802.07956)

##### PDF
[http://arxiv.org/pdf/1802.07956](http://arxiv.org/pdf/1802.07956)

