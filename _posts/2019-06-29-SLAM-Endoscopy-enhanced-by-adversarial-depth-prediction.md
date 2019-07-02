---
layout: post
title: "SLAM Endoscopy enhanced by adversarial depth prediction"
date: 2019-06-29 21:42:42
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Prediction SLAM
author: Richard J. Chen, Taylor L. Bobrow, Thomas Athey, Faisal Mahmood, Nicholas J. Durr
mathjax: true
---

* content
{:toc}

##### Abstract
Medical endoscopy remains a challenging application for simultaneous localization and mapping (SLAM) due to the sparsity of image features and size constraints that prevent direct depth-sensing. We present a SLAM approach that incorporates depth predictions made by an adversarially-trained convolutional neural network (CNN) applied to monocular endoscopy images. The depth network is trained with synthetic images of a simple colon model, and then fine-tuned with domain-randomized, photorealistic images rendered from computed tomography measurements of human colons. Each image is paired with an error-free depth map for supervised adversarial learning. Monocular RGB images are then fused with corresponding depth predictions, enabling dense reconstruction and mosaicing as an endoscope is advanced through the gastrointestinal tract. Our preliminary results demonstrate that incorporating monocular depth estimation into a SLAM architecture can enable dense reconstruction of endoscopic scenes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00283](http://arxiv.org/abs/1907.00283)

##### PDF
[http://arxiv.org/pdf/1907.00283](http://arxiv.org/pdf/1907.00283)

