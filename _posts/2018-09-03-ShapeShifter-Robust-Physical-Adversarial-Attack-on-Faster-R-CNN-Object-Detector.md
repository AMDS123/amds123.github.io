---
layout: post
title: "ShapeShifter: Robust Physical Adversarial Attack on Faster R-CNN Object Detector"
date: 2018-09-03 02:22:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Image_Classification Classification Detection
author: Shang-Tse Chen, Cory Cornelius, Jason Martin, Duen Horng Chau
mathjax: true
---

* content
{:toc}

##### Abstract
Given the ability to directly manipulate image pixels in the digital input space, an adversary can easily generate imperceptible perturbations to fool a Deep Neural Network (DNN) image classifier, as demonstrated in prior work. In this work, we propose ShapeShifter, an attack that tackles the more challenging problem of crafting physical adversarial perturbations to fool image-based object detectors like Faster R-CNN. Attacking an object detector is more difficult than attacking an image classifier, as it needs to mislead the classification results in multiple bounding boxes with different scales. Extending the digital attack to the physical world adds another layer of difficulty, because it requires the perturbation to be robust enough to survive real-world distortions due to different viewing distances and angles, lighting conditions, and camera limitations. We show that the Expectation over Transformation technique, which was originally proposed to enhance the robustness of adversarial perturbations in image classification, can be successfully adapted to the object detection setting. ShapeShifter can generate adversarially perturbed stop signs that are consistently mis-detected by Faster R-CNN as other objects, posing a potential threat to autonomous vehicles and other safety-critical computer vision systems.

##### Abstract (translated by Google)
鉴于能够直接操纵数字输入空间中的图像像素，对手可以轻易地产生难以察觉的扰动以欺骗深度神经网络（DNN）图像分类器，如先前的工作所示。在这项工作中，我们提出了ShapeShifter，这是一种攻击，可以解决制造物理对抗性扰动的更具挑战性的问题，以愚弄基于图像的物体探测器，如Faster R-CNN。攻击对象检测器比攻击图像分类器更困难，因为它需要在具有不同比例的多个边界框中误导分类结果。将数字攻击扩展到物理世界增加了另一层难度，因为它需要足够强大的扰动以承受由于不同的观看距离和角度，照明条件和相机限制而导致的真实世界的失真。我们表明，最初提出的用于增强图像分类中对抗性扰动的鲁棒性的转换期望技术可以成功地适应对象检测设置。 ShapeShifter可以产生异常扰动的停止标志，这些标志一直被更快的R-CNN误检测为其他物体，对自动驾驶汽车和其他安全关键的计算机视觉系统构成潜在威胁。

##### URL
[http://arxiv.org/abs/1804.05810](http://arxiv.org/abs/1804.05810)

##### PDF
[http://arxiv.org/pdf/1804.05810](http://arxiv.org/pdf/1804.05810)

