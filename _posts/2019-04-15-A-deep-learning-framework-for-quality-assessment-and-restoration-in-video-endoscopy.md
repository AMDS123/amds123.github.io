---
layout: post
title: "A deep learning framework for quality assessment and restoration in video endoscopy"
date: 2019-04-15 14:26:38
categories: arXiv_AI
tags: arXiv_AI Regularization Adversarial Object_Detection GAN CNN Deep_Learning Detection
author: Sharib Ali, Felix Zhou, Adam Bailey, Barbara Braden, James East, Xin Lu, Jens Rittscher
mathjax: true
---

* content
{:toc}

##### Abstract
Endoscopy is a routine imaging technique used for both diagnosis and minimally invasive surgical treatment. Artifacts such as motion blur, bubbles, specular reflections, floating objects and pixel saturation impede the visual interpretation and the automated analysis of endoscopy videos. Given the widespread use of endoscopy in different clinical applications, we contend that the robust and reliable identification of such artifacts and the automated restoration of corrupted video frames is a fundamental medical imaging problem. Existing state-of-the-art methods only deal with the detection and restoration of selected artifacts. However, typically endoscopy videos contain numerous artifacts which motivates to establish a comprehensive solution. 
 We propose a fully automatic framework that can: 1) detect and classify six different primary artifacts, 2) provide a quality score for each frame and 3) restore mildly corrupted frames. To detect different artifacts our framework exploits fast multi-scale, single stage convolutional neural network detector. We introduce a quality metric to assess frame quality and predict image restoration success. Generative adversarial networks with carefully chosen regularization are finally used to restore corrupted frames. 
 Our detector yields the highest mean average precision (mAP at 5% threshold) of 49.0 and the lowest computational time of 88 ms allowing for accurate real-time processing. Our restoration models for blind deblurring, saturation correction and inpainting demonstrate significant improvements over previous methods. On a set of 10 test videos we show that our approach preserves an average of 68.7% which is 25% more frames than that retained from the raw videos.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07073](http://arxiv.org/abs/1904.07073)

##### PDF
[http://arxiv.org/pdf/1904.07073](http://arxiv.org/pdf/1904.07073)

