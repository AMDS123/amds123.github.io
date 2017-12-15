---
layout: post
title: "Detection and Attention: Diagnosing Pulmonary Lung Cancer from CT by Imitating Physicians"
date: 2017-12-14 07:34:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Detection
author: Ning Li, Haopeng Liu, Bin Qiu, Wei Guo, Shijun Zhao, Kungang Li, Jie He
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel and efficient method to build a Computer-Aided Diagnoses (CAD) system for lung nodule detection based on Computed Tomography (CT). This task was treated as an Object Detection on Video (VID) problem by imitating how a radiologist reads CT scans. A lung nodule detector was trained to automatically learn nodule features from still images to detect lung nodule candidates with both high recall and accuracy. Unlike previous work which used 3-dimensional information around the nodule to reduce false positives, we propose two simple but efficient methods, Multi-slice propagation (MSP) and Motionless-guide suppression (MLGS), which analyze sequence information of CT scans to reduce false negatives and suppress false positives. We evaluated our method in open-source LUNA16 dataset which contains 888 CT scans, and obtained state-of-the-art result (Free-Response Receiver Operating Characteristic score of 0.892) with detection speed (end to end within 20 seconds per patient on a single NVidia GTX 1080) much higher than existing methods.

##### Abstract (translated by Google)
本文提出了一种基于计算机断层扫描（CT）建立肺结节检测计算机辅助诊断（CAD）系统的新颖有效的方法。通过模仿放射科医师如何读取CT扫描，将此任务视为视频对象检测（VID）问题。训练肺结节检测器，从静止图像自动学习结节特征，以高回忆率和准确性检测肺结节候选者。与以前在结节周围使用三维信息以减少假阳性的工作不同，我们提出了两种简单但有效的方法，即多切片传播（MSP）和无运动引导抑制（MLGS），其分析CT扫描的序列信息以减少假阴性和抑制误报。我们在包含888个CT扫描的开源LUNA16数据库中评估了我们的方法，并且获得了具有检测速度的最新结果（自由应答接收者操作特征评分为0.892）（每个患者在20秒内端对端一个NVidia GTX 1080）比现有的方法高得多。

##### URL
[http://arxiv.org/abs/1712.05114](http://arxiv.org/abs/1712.05114)

##### PDF
[http://arxiv.org/pdf/1712.05114](http://arxiv.org/pdf/1712.05114)

