---
layout: post
title: "Soft Sampling for Robust Object Detection"
date: 2018-06-18 23:40:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Zhe Wu, Navaneeth Bodla, Bharat Singh, Mahyar Najibi, Rama Chellappa, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We study the robustness of object detection under the presence of missing annotations. In this setting, the unlabeled object instances will be treated as background, which will generate an incorrect training signal for the detector. Interestingly, we observe that after dropping 30% of the annotations (and labeling them as background), the performance of CNN-based object detectors like Faster-RCNN only drops by 5% on the PASCAL VOC dataset. We provide a detailed explanation for this result. To further bridge the performance gap, we propose a simple yet effective solution, called Soft Sampling. Soft Sampling re-weights the gradients of RoIs as a function of overlap with positive instances. This ensures that the uncertain background regions are given a smaller weight compared to the hardnegatives. Extensive experiments on curated PASCAL VOC datasets demonstrate the effectiveness of the proposed Soft Sampling method at different annotation drop rates. Finally, we show that on OpenImagesV3, which is a real-world dataset with missing annotations, Soft Sampling outperforms standard detection baselines by over 3%.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.06986](https://arxiv.org/abs/1806.06986)

##### PDF
[https://arxiv.org/pdf/1806.06986](https://arxiv.org/pdf/1806.06986)

