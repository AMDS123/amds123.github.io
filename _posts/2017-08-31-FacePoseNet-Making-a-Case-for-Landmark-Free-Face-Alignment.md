---
layout: post
title: "FacePoseNet: Making a Case for Landmark-Free Face Alignment"
date: 2017-08-31 22:17:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Recognition Face_Recognition
author: Fengju Chang, Anh Tuan Tran, Tal Hassner, Iacopo Masi, Ram Nevatia, Gerard Medioni
mathjax: true
---

* content
{:toc}

##### Abstract
We show how a simple convolutional neural network (CNN) can be trained to accurately and robustly regress 6 degrees of freedom (6DoF) 3D head pose, directly from image intensities. We further explain how this FacePoseNet (FPN) can be used to align faces in 2D and 3D as an alternative to explicit facial landmark detection for these tasks. We claim that in many cases the standard means of measuring landmark detector accuracy can be misleading when comparing different face alignments. Instead, we compare our FPN with existing methods by evaluating how they affect face recognition accuracy on the IJB-A and IJB-B benchmarks: using the same recognition pipeline, but varying the face alignment method. Our results show that (a) better landmark detection accuracy measured on the 300W benchmark does not necessarily imply better face recognition accuracy. (b) Our FPN provides superior 2D and 3D face alignment on both benchmarks. Finally, (c), FPN aligns faces at a small fraction of the computational cost of comparably accurate landmark detectors. For many purposes, FPN is thus a far faster and far more accurate face alignment method than using facial landmark detectors.

##### Abstract (translated by Google)
我们展示了一个简单的卷积神经网络（CNN）如何能够被训练成直接从图像强度中准确和稳健地回归6个自由度（6DoF）的3D头部姿态。我们进一步解释如何使用FacePoseNet（FPN）在2D和3D中对齐人脸，作为这些任务的显式面部标志检测的替代方案。我们声称，在许多情况下，比较不同的面对齐时，测量标志检测器准确度的标准手段可能是误导性的。相反，我们比较我们的FPN和现有的方法，通过评估它们如何影响IJB-A和IJB-B基准面的人脸识别准确性：使用相同的识别流水线，但是改变面部对准方法。我们的结果表明（a）在300W基准测量的更好的标志检测精度不一定意味着更好的面部识别精度。 （b）我们的FPN在两个基准上都提供了出众的2D和3D人脸对齐。最后，（c），FPN将人脸对准的准确度相近的标志性检测器的计算成本的一小部分。对于许多目的而言，FPN因此比使用面部标志检测器更快，更准确的面对准方法。

##### URL
[https://arxiv.org/abs/1708.07517](https://arxiv.org/abs/1708.07517)

##### PDF
[https://arxiv.org/pdf/1708.07517](https://arxiv.org/pdf/1708.07517)

