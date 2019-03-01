---
layout: post
title: "CMR motion artifact correction using generative adversarial nets"
date: 2019-02-21 12:39:23
categories: arXiv_CV
tags: arXiv_CV Adversarial Deep_Learning Detection
author: Yunxuan Zhang, Weiliang Zhang, Qinyan Zhang, Jijiang Yang, Xiuyu Chen, Shihua Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiovascular Magnetic Resonance (CMR) plays an important role in the diagnoses and treatment of cardiovascular diseases while motion artifacts which are formed during the scanning process of CMR seriously affects doctors to find the exact focus. The current correction methods mainly focus on the K-space which is a grid of raw data obtained from the MR signal directly and then transfer to CMR image by inverse Fourier transform. They are neither effective nor efficient and can not be utilized in clinic. In this paper, we propose a novel approach for CMR motion artifact correction using deep learning. Specially, we use deep residual network (ResNet) as net framework and train our model in adversarial manner. Our approach is motivated by the connection between image motion blur and CMR motion artifact, so we can transfer methods from motion-deblur where deep learning has made great progress to CMR motion-correction successfully. To evaluate motion artifact correction methods, we propose a novel algorithm on how edge detection results are improved by deblurred algorithm. Boosted by deep learning and adversarial training algorithm, our model is trainable in an end-to-end manner, can be tested in real-time and achieves the state-of-art results for CMR correction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11121](http://arxiv.org/abs/1902.11121)

##### PDF
[http://arxiv.org/pdf/1902.11121](http://arxiv.org/pdf/1902.11121)

