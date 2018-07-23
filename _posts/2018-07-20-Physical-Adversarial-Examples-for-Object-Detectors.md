---
layout: post
title: "Physical Adversarial Examples for Object Detectors"
date: 2018-07-20 10:14:27
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Deep_Learning Prediction Detection
author: Kevin Eykholt, Ivan Evtimov, Earlence Fernandes, Bo Li, Amir Rahmati, Florian Tramer, Atul Prakash, Tadayoshi Kohno, Dawn Song
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) are vulnerable to adversarial examples-maliciously crafted inputs that cause DNNs to make incorrect predictions. Recent work has shown that these attacks generalize to the physical domain, to create perturbations on physical objects that fool image classifiers under a variety of real-world conditions. Such attacks pose a risk to deep learning models used in safety-critical cyber-physical systems. In this work, we extend physical attacks to more challenging object detection models, a broader class of deep learning algorithms widely used to detect and label multiple objects within a scene. Improving upon a previous physical attack on image classifiers, we create perturbed physical objects that are either ignored or mislabeled by object detection models. We implement a Disappearance Attack, in which we cause a Stop sign to "disappear" according to the detector-either by covering thesign with an adversarial Stop sign poster, or by adding adversarial stickers onto the sign. In a video recorded in a controlled lab environment, the state-of-the-art YOLOv2 detector failed to recognize these adversarial Stop signs in over 85% of the video frames. In an outdoor experiment, YOLO was fooled by the poster and sticker attacks in 72.5% and 63.5% of the video frames respectively. We also use Faster R-CNN, a different object detection model, to demonstrate the transferability of our adversarial perturbations. The created poster perturbation is able to fool Faster R-CNN in 85.9% of the video frames in a controlled lab environment, and 40.2% of the video frames in an outdoor environment. Finally, we present preliminary results with a new Creation Attack, where in innocuous physical stickers fool a model into detecting nonexistent objects.

##### Abstract (translated by Google)
深度神经网络（DNN）容易受到对抗性示例的攻击 - 恶意制作的输入会导致DNN做出错误的预测。最近的工作表明，这些攻击一般化到物理领域，在物理对象上产生扰动，在各种现实条件下欺骗图像分类器。此类攻击对安全关键型网络物理系统中使用的深度学习模型构成风险。在这项工作中，我们将物理攻击扩展到更具挑战性的对象检测模型，这是一类广泛的深度学习算法，广泛用于检测和标记场景中的多个对象。改进先前对图像分类器的物理攻击，我们创建被对象检测模型忽略或错误标记的扰动物理对象。我们实施了一个消失攻击，我们根据探测器使停车标志“消失” - 通过用对抗性停止标志海报覆盖标志，或者在标志上添加对抗贴纸。在受控实验室环境中录制的视频中，最先进的YOLOv2探测器无法识别超过85％的视频帧中的这些对抗性停止标志。在一次户外实验中，YOLO被海报和贴纸分别愚弄了72.5％和63.5％的视频帧。我们还使用更快的R-CNN，一种不同的物体检测模型，来证明我们的对抗性扰动的可转移性。创建的海报扰动能够在受控实验室环境中愚弄更快的R-CNN 85.9％的视频帧，在室外环境中愚弄40.2％的视频帧。最后，我们提出了一个新的创造攻击的初步结果，在无害的物理贴纸中欺骗模型来检测不存在的对象。

##### URL
[http://arxiv.org/abs/1807.07769](http://arxiv.org/abs/1807.07769)

##### PDF
[http://arxiv.org/pdf/1807.07769](http://arxiv.org/pdf/1807.07769)

