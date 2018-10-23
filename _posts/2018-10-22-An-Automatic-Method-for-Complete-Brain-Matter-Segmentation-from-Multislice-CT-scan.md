---
layout: post
title: "An Automatic Method for Complete Brain Matter Segmentation from Multislice CT scan"
date: 2018-10-22 07:11:06
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Soumi Ray, Vinod Kumar, Chirag Ahuja, Niranjan Khandelwal
mathjax: true
---

* content
{:toc}

##### Abstract
Computed tomography imaging is well accepted for its imaging speed, image contrast &amp; resolution and cost. Thus it has wide use in detection and diagnosis of brain diseases. But unfortunately reported works on CT segmentation is not very significant. In this paper, a robust automatic segmentation system is presented which is capable of segment complete brain matter from CT slices, without any lose in information. The proposed method is simple, fast, accurate and completely automatic. It can handle multislice CT scan in single run. From a given multislice CT dataset, one slice is selected automatically to form masks for segmentation. Two types of masks are created to handle nasal slices in a better way. Masks are created from selected reference slice using automatic seed point selection and region growing technique. One mask is designed for brain matter and another includes the skull of the reference slice. This second mask is used as global reference mask for all slices whereas the brain matter mask is implemented on only adjacent slices and continuously modified for better segmentation. Slices in given dataset are divided into two batches, before reference slice and after reference slice. Each batch segmented separately. Successive propagation of brain matter mask has demonstrated very high potential in reported segmentation. Presented result shows highest sensitivity and more than 96% accuracy in all cases. Resulted segmented images can be used for any brain disease diagnosis or further image analysis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.06215](http://arxiv.org/abs/1809.06215)

##### PDF
[http://arxiv.org/pdf/1809.06215](http://arxiv.org/pdf/1809.06215)

