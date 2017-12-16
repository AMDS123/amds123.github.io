---
layout: post
title: "Automatic Tool Landmark Detection for Stereo Vision in Robot-Assisted Retinal Surgery"
date: 2017-11-20 17:59:08
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Quantitative Detection
author: Thomas Probst, Kevis-Kokitsi Maninis, Ajad Chhatkuli, Mouloud Ourak, Emmanuel Vander Poorten, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision and robotics are being increasingly applied in medical interventions. Especially in interventions where extreme precision is required they could make a difference. One such application is robot-assisted retinal microsurgery. In recent works, such interventions are conducted under a stereo-microscope, and with a robot-controlled surgical tool. The complementarity of computer vision and robotics has however not yet been fully exploited. In order to improve the robot control we are interested in 3D reconstruction of the anatomy and in automatic tool localization using a stereo microscope. In this paper, we solve this problem for the first time using a single pipeline, starting from uncalibrated cameras to reach metric 3D reconstruction and registration, in retinal microsurgery. The key ingredients of our method are: (a) surgical tool landmark detection, and (b) 3D reconstruction with the stereo microscope, using the detected landmarks. To address the former, we propose a novel deep learning method that detects and recognizes keypoints in high definition images at higher than real-time speed. We use the detected 2D keypoints along with their corresponding 3D coordinates obtained from the robot sensors to calibrate the stereo microscope using an affine projection model. We design an online 3D reconstruction pipeline that makes use of smoothness constraints and performs robot-to-camera registration. The entire pipeline is extensively validated on open-sky porcine eye sequences. Quantitative and qualitative results are presented for all steps.

##### Abstract (translated by Google)
计算机视觉和机器人技术正在越来越多地应用于医疗干预。尤其是在需要极高精度的干预中，他们可能会有所作为。一种这样的应用是机器人辅助的视网膜显微手术。在最近的工作中，这样的干预是在立体显微镜下进行的，并且使用机器人控制的手术工具。计算机视觉和机器人技术的互补性尚未被充分利用。为了改善机器人的控制，我们感兴趣的三维重建的解剖和自动工具定位使用立体显微镜。在本文中，我们首次使用单一管道解决了这个问题，从未校准的相机开始，在视网膜显微手术中进行公制三维重建和配准。我们的方法的关键成分是：（a）手术工具界标检测，和（b）使用体视显微镜的3D重建，使用检测到的界标。为了解决前者，我们提出了一种新颖的深度学习方法，以高于实时的速度检测和识别高清图像中的关键点。我们使用检测到的2D关键点以及从机器人传感器获得的相应3D坐标，使用仿射投影模型来校准立体显微镜。我们设计了一个利用平滑约束的在线3D重建流水线，并执行机器人到摄影机的注册。整个管道在开阔的猪眼序列上得到了广泛的验证。为所有步骤提供定量和定性结果。

##### URL
[https://arxiv.org/abs/1709.05665](https://arxiv.org/abs/1709.05665)

##### PDF
[https://arxiv.org/pdf/1709.05665](https://arxiv.org/pdf/1709.05665)

