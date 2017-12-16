---
layout: post
title: "DeepIGeoS: A Deep Interactive Geodesic Framework for Medical Image Segmentation"
date: 2017-09-19 08:48:14
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Prediction
author: Guotai Wang, Maria A. Zuluaga, Wenqi Li, Rosalind Pratt, Premal A. Patel, Michael Aertsen, Tom Doel, Anna L. David, Jan Deprest, Sebastien Ourselin, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate medical image segmentation is essential for diagnosis, surgical planning and many other applications. Convolutional Neural Networks (CNNs) have become the state-of-the-art automatic segmentation methods. However, fully automatic results may still need to be refined to become accurate and robust enough for clinical use. We propose a deep learning-based interactive segmentation method to improve the results obtained by an automatic CNN and to reduce user interactions during refinement for higher accuracy. We use one CNN to obtain an initial automatic segmentation, on which user interactions are added to indicate mis-segmentations. Another CNN takes as input the user interactions with the initial segmentation and gives a refined result. We propose to combine user interactions with CNNs through geodesic distance transforms, and propose a resolution-preserving network that gives a better dense prediction. In addition, we integrate user interactions as hard constraints into a back-propagatable Conditional Random Field. We validated the proposed framework in the context of 2D placenta segmentation from fetal MRI and 3D brain tumor segmentation from FLAIR images. Experimental results show our method achieves a large improvement from automatic CNNs, and obtains comparable and even higher accuracy with fewer user interventions and less time compared with traditional interactive methods.

##### Abstract (translated by Google)
精确的医学图像分割对诊断，手术规划和许多其他应用至关重要。卷积神经网络（CNN）已经成为最先进的自动分割方法。然而，完全自动的结果可能仍然需要进一步完善，以便在临床使用时变得准确和可靠。我们提出了一种基于深度学习的交互式分割方法，以改善自动CNN获得的结果，并在精确化过程中减少用户交互以提高准确性。我们使用一个CNN来获得一个初始的自动分割，在这个分割上添加用户交互以指示错误分割。另一个CNN将用户与初始分割的交互作为输入，并给出精确的结果。我们建议通过测地距离变换将用户交互与CNN结合起来，并提出一个分辨率保持网络，以提供更好的密集预测。另外，我们将用户交互作为硬约束集成到可反向传播的条件随机场中。我们验证了提出的框架在胎儿MRI的二维胎盘分割和FLAIR图像的三维脑肿瘤分割的背景下。实验结果表明，与传统的交互式方法相比，我们的方法在自动CNN方面取得了较大的进步，获得了可比性甚至更高的准确性，用户干预更少，时间更少。

##### URL
[https://arxiv.org/abs/1707.00652](https://arxiv.org/abs/1707.00652)

##### PDF
[https://arxiv.org/pdf/1707.00652](https://arxiv.org/pdf/1707.00652)

