---
layout: post
title: "Adaloss: Adaptive Loss Function for Landmark Localization"
date: 2019-08-02 21:18:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Deep_Learning Detection
author: Brian Teixeira, Birgi Tamersoy, Vivek Singh, Ankur Kapoor
mathjax: true
---

* content
{:toc}

##### Abstract
Landmark localization is a challenging problem in computer vision with a multitude of applications. Recent deep learning based methods have shown improved results by regressing likelihood maps instead of regressing the coordinates directly. However, setting the precision of these regression targets during the training is a cumbersome process since it creates a trade-off between trainability vs localization accuracy. Using precise targets introduces a significant sampling bias and hence makes the training more difficult, whereas using imprecise targets results in inaccurate landmark detectors. In this paper, we introduce "Adaloss", an objective function that adapts itself during the training by updating the target precision based on the training statistics. This approach does not require setting problem-specific parameters and shows improved stability in training and better localization accuracy during inference. We demonstrate the effectiveness of our proposed method in three different applications of landmark localization: 1) the challenging task of precisely detecting catheter tips in medical X-ray images, 2) localizing surgical instruments in endoscopic images, and 3) localizing facial features on in-the-wild images where we show state-of-the-art results on the 300-W benchmark dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01070](http://arxiv.org/abs/1908.01070)

##### PDF
[http://arxiv.org/pdf/1908.01070](http://arxiv.org/pdf/1908.01070)

