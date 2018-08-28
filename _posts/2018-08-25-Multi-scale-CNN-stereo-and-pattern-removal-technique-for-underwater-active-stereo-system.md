---
layout: post
title: "Multi-scale CNN stereo and pattern removal technique for underwater active stereo system"
date: 2018-08-25 03:17:16
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Kazuto Ichimaru, Ryo Furukawa, Hiroshi Kawasaki
mathjax: true
---

* content
{:toc}

##### Abstract
Demands on capturing dynamic scenes of underwater environments are rapidly growing. Passive stereo is applicable to capture dynamic scenes, however the shape with textureless surfaces or irregular reflections cannot be recovered by the technique. In our system, we add a pattern projector to the stereo camera pair so that artificial textures are augmented on the objects. To use the system at underwater environments, several problems should be compensated, i.e., refraction, disturbance by fluctuation and bubbles. Further, since surface of the objects are interfered by the bubbles, projected patterns, etc., those noises and patterns should be removed from captured images to recover original texture. To solve these problems, we propose three approaches; a depth-dependent calibration, Convolutional Neural Network(CNN)-stereo method and CNN-based texture recovery method. A depth-dependent calibration is our analysis to find the acceptable depth range for approximation by center projection to find the certain target depth for calibration. In terms of CNN stereo, unlike common CNNbased stereo methods which do not consider strong disturbances like refraction or bubbles, we designed a novel CNN architecture for stereo matching using multi-scale information, which is intended to be robust against such disturbances. Finally, we propose a multi-scale method for bubble and a projected-pattern removal method using CNNs to recover original textures. Experimental results are shown to prove the effectiveness of our method compared with the state of the art techniques. Furthermore, reconstruction of a live swimming fish is demonstrated to confirm the feasibility of our techniques.

##### Abstract (translated by Google)
捕捉水下环境动态场景的需求正在迅速增长。被动立体声适用于捕捉动态场景，但是具有无纹理表面或不规则反射的形状不能通过该技术恢复。在我们的系统中，我们在立体相机对中添加了一个图案投影仪，以便在对象上增加人造纹理。为了在水下环境中使用该系统，应该补偿几个问题，即折射，波动和气泡的干扰。此外，由于物体的表面受到气泡，投射图案等的干扰，因此应当从捕获的图像中去除那些噪声和图案以恢复原始纹理。为了解决这些问题，我们提出了三种方法;深度相关校准，卷积神经网络（CNN） - 立体方法和基于CNN的纹理恢复方法。深度相关校准是我们的分析，以找到可接受的深度范围，用于通过中心投影来近似以找到用于校准的特定目标深度。就CNN立体声而言，与不考虑折射或气泡等强干扰的常见基于CNN的立体声方法不同，我们设计了一种新的CNN架构，用于使用多尺度信息进行立体匹配，旨在抵抗这种干扰。最后，我们提出了一种多尺度的气泡方法和一种使用CNN来恢复原始纹理的投影图案去除方法。实验结果证明了我们的方法与现有技术相比的有效性。此外，证明了活鱼的重建证实了我们的技术的可行性。

##### URL
[http://arxiv.org/abs/1808.08348](http://arxiv.org/abs/1808.08348)

##### PDF
[http://arxiv.org/pdf/1808.08348](http://arxiv.org/pdf/1808.08348)

