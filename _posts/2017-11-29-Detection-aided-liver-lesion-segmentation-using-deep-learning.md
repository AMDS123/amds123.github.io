---
layout: post
title: 'Detection-aided liver lesion segmentation using deep learning'
date: 2017-11-29 19:27:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Deep_Learning Detection
author: Miriam Bellver, Kevis-Kokitsi Maninis, Jordi Pont-Tuset, Xavier Giro-i-Nieto, Jordi Torres, Luc Van Gool
---

* content
{:toc}

##### Abstract
A fully automatic technique for segmenting the liver and localizing its unhealthy tissues is a convenient tool in order to diagnose hepatic diseases and assess the response to the according treatments. In this work we propose a method to segment the liver and its lesions from Computed Tomography (CT) scans using Convolutional Neural Networks (CNNs), that have proven good results in a variety of computer vision tasks, including medical imaging. The network that segments the lesions consists of a cascaded architecture, which first focuses on the region of the liver in order to segment the lesions on it. Moreover, we train a detector to localize the lesions, and mask the results of the segmentation network with the positive detections. The segmentation architecture is based on DRIU, a Fully Convolutional Network (FCN) with side outputs that work on feature maps of different resolutions, to finally benefit from the multi-scale information learned by different stages of the network. The main contribution of this work is the use of a detector to localize the lesions, which we show to be beneficial to remove false positives triggered by the segmentation network. Source code and models are available at this https URL .

##### Abstract (translated by Google)
一种全自动的分割肝脏和定位其不健康组织的方法是诊断肝脏疾病和评估对相应治疗反应的便利工具。在这项工作中，我们提出了一种使用卷积神经网络（CNN）对来自计算机断层扫描（CT）扫描的肝脏及其病变进行分割的方法，其已经在各种计算机视觉任务（包括医学成像）中证明了良好的结果。细分病变的网络由一个级联结构组成，该结构首先集中在肝脏区域，以分割病变。此外，我们训练检测器来定位病变，并用正检测掩盖分割网络的结果。分割体系结构基于DRIU，一个完全卷积网络（FCN），具有在不同分辨率的特征图上工作的侧面输出，最终受益于网络不同阶段学到的多尺度信息。这项工作的主要贡献是使用检测器来定位病变，我们表明这有利于消除由分割网络触发的误报。源代码和模型可在此https网址获得。

##### URL
[https://arxiv.org/abs/1711.11069](https://arxiv.org/abs/1711.11069)

