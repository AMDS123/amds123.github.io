---
layout: post
title: "Lung segmentation on chest x-ray images in patients with severe abnormal findings using deep learning"
date: 2019-08-21 04:05:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Deep_Learning
author: Mizuho Nishio, Koji Fujimoto, Kaori Togashi
mathjax: true
---

* content
{:toc}

##### Abstract
Rationale and objectives: Several studies have evaluated the usefulness of deep learning for lung segmentation using chest x-ray (CXR) images with small- or medium-sized abnormal findings. Here, we built a database including both CXR images with severe abnormalities and experts' lung segmentation results, and aimed to evaluate our network's efficacy in lung segmentation from these images. Materials and Methods: For lung segmentation, CXR images from the Japanese Society of Radiological Technology (JSRT, N = 247) and Montgomery databases (N = 138), were included, and 65 additional images depicting severe abnormalities from a public database were evaluated and annotated by a radiologist, thereby adding lung segmentation results to these images. Baseline U-net was used to segment the lungs in images from the three databases. Subsequently, the U-net network architecture was automatically optimized for lung segmentation from CXR images using Bayesian optimization. Dice similarity coefficient (DSC) was calculated to confirm segmentation. Results: Our results demonstrated that using baseline U-net yielded poorer lung segmentation results in our database than those in the JSRT and Montgomery databases, implying that robust segmentation of lungs may be difficult because of severe abnormalities. The DSC values with baseline U-net for the JSRT, Montgomery and our databases were 0.979, 0.941, and 0.889, respectively, and with optimized U-net, 0.976, 0.973, and 0.932, respectively. Conclusion: For robust lung segmentation, the U-net architecture was optimized via Bayesian optimization, and our results demonstrate that the optimized U-net was more robust than baseline U-net in lung segmentation from CXR images with large-sized abnormalities.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07704](http://arxiv.org/abs/1908.07704)

##### PDF
[http://arxiv.org/pdf/1908.07704](http://arxiv.org/pdf/1908.07704)

