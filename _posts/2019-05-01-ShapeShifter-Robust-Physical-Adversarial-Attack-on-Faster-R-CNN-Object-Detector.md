---
layout: post
title: "ShapeShifter: Robust Physical Adversarial Attack on Faster R-CNN Object Detector"
date: 2019-05-01 03:41:44
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


##### URL
[http://arxiv.org/abs/1804.05810](http://arxiv.org/abs/1804.05810)

##### PDF
[http://arxiv.org/pdf/1804.05810](http://arxiv.org/pdf/1804.05810)

