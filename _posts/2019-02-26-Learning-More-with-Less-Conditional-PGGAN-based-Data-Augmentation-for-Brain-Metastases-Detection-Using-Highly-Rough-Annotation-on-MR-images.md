---
layout: post
title: "Learning More with Less: Conditional PGGAN-based Data Augmentation for Brain Metastases Detection Using Highly-Rough Annotation on MR images"
date: 2019-02-26 10:46:53
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Detection VQA
author: Changhee Han, Kohei Murao, Tomoyuki Noguchi, Yusuke Kawata, Fumiya Uchiyama, Leonardo Rundo, Hideki Nakayama, Shin&#x27;ichi Satoh
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate computer-assisted diagnosis can alleviate the risk of overlooking the diagnosis in a clinical environment. Towards this, as a Data Augmentation (DA) technique, Generative Adversarial Networks (GANs) can synthesize additional training data to handle small/fragmented medical images from various scanners; those images are realistic but completely different from the original ones, filling the data lack in the real image distribution. However, we cannot easily use them to locate the position of disease areas, considering expert physicians' annotation as time-expensive tasks. Therefore, this paper proposes Conditional Progressive Growing of GANs (CPGGANs), incorporating bounding box conditions into PGGANs to place brain metastases at desired position/size on 256 x 256 Magnetic Resonance (MR) images, for Convolutional Neural Network-based tumor detection; this first GAN-based medical DA using automatic bounding box annotation improves the robustness during training. The results show that CPGGAN-based DA can boost 10% sensitivity in diagnosis with an acceptable amount of additional False Positives---even with physicians' highly-rough and inconsistent bounding box annotation. Surprisingly, further realistic tumor appearance, achieved with additional normal brain MR images for CPGGAN training, does not contribute to detection performance, while even three expert physicians cannot accurately distinguish them from the real ones in Visual Turing Test.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09856](http://arxiv.org/abs/1902.09856)

##### PDF
[http://arxiv.org/pdf/1902.09856](http://arxiv.org/pdf/1902.09856)

