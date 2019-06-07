---
layout: post
title: "Improving RetinaNet for CT Lesion Detection with Dense Masks from Weak RECIST Labels"
date: 2019-06-05 20:04:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Martin Zlocha, Qi Dou, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate, automated lesion detection in Computed Tomography (CT) is an important yet challenging task due to the large variation of lesion types, sizes, locations and appearances. Recent work on CT lesion detection employs two-stage region proposal based methods trained with centroid or bounding-box annotations. We propose a highly accurate and efficient one-stage lesion detector, by re-designing a RetinaNet to meet the particular challenges in medical imaging. Specifically, we optimize the anchor configurations using a differential evolution search algorithm. For training, we leverage the response evaluation criteria in solid tumors (RECIST) annotation which are measured in clinical routine. We incorporate dense masks from weak RECIST labels, obtained automatically using GrabCut, into the training objective, which in combination with other advancements yields new state-of-the-art performance. We evaluate our method on the public DeepLesion benchmark, consisting of 32,735 lesions across the body. Our one-stage detector achieves a sensitivity of 90.77% at 4 false positives per image, significantly outperforming the best reported methods by over 5%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02283](http://arxiv.org/abs/1906.02283)

##### PDF
[http://arxiv.org/pdf/1906.02283](http://arxiv.org/pdf/1906.02283)

