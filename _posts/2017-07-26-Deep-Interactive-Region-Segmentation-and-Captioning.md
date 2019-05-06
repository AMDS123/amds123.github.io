---
layout: post
title: "Deep Interactive Region Segmentation and Captioning"
date: 2017-07-26 10:40:33
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Knowledge Segmentation Caption CNN Deep_Learning Detection
author: Ali Sharifi Boroujerdi, Maryam Khanian, Michael Breuss
mathjax: true
---

* content
{:toc}

##### Abstract
With recent innovations in dense image captioning, it is now possible to describe every object of the scene with a caption while objects are determined by bounding boxes. However, interpretation of such an output is not trivial due to the existence of many overlapping bounding boxes. Furthermore, in current captioning frameworks, the user is not able to involve personal preferences to exclude out of interest areas. In this paper, we propose a novel hybrid deep learning architecture for interactive region segmentation and captioning where the user is able to specify an arbitrary region of the image that should be processed. To this end, a dedicated Fully Convolutional Network (FCN) named Lyncean FCN (LFCN) is trained using our special training data to isolate the User Intention Region (UIR) as the output of an efficient segmentation. In parallel, a dense image captioning model is utilized to provide a wide variety of captions for that region. Then, the UIR will be explained with the caption of the best match bounding box. To the best of our knowledge, this is the first work that provides such a comprehensive output. Our experiments show the superiority of the proposed approach over state-of-the-art interactive segmentation methods on several well-known datasets. In addition, replacement of the bounding boxes with the result of the interactive segmentation leads to a better understanding of the dense image captioning output as well as accuracy enhancement for the object detection in terms of Intersection over Union (IoU).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.08364](https://arxiv.org/abs/1707.08364)

##### PDF
[https://arxiv.org/pdf/1707.08364](https://arxiv.org/pdf/1707.08364)

