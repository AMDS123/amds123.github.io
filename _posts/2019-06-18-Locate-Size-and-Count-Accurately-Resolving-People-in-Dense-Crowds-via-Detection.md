---
layout: post
title: "Locate, Size and Count: Accurately Resolving People in Dense Crowds via Detection"
date: 2019-06-18 12:58:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Face Prediction Detection
author: Deepak Babu Sam, Skand Vishwanath Peri, Mukuntha N. S., Amogh Kamath, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a detection framework for dense crowd counting and eliminate the need for the prevalent density regression paradigm. Typical counting models predict crowd density for an image as opposed to detecting every person. These regression methods, in general, fail to localize persons accurate enough for most applications other than counting. Hence, we adopt an architecture that locates every person in the crowd, sizes the spotted heads with bounding box and then counts them. Compared to normal object or face detectors, there exist certain unique challenges in designing such a detection system. Some of them are direct consequences of the huge diversity in dense crowds along with the need to predict boxes contiguously. We solve these issues and develop our LSC-CNN model, which can reliably detect heads of people across sparse to dense crowds. LSC-CNN employs a multi-column architecture with top-down feedback processing to better resolve persons and produce refined predictions at multiple resolutions. Interestingly, the proposed training regime requires only point head annotation, but can estimate approximate size information of heads. We show that LSC-CNN not only has superior localization than existing density regressors, but outperforms in counting as well. The code for our approach is available at https://github.com/val-iisc/lsc-cnn.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07538](http://arxiv.org/abs/1906.07538)

##### PDF
[http://arxiv.org/pdf/1906.07538](http://arxiv.org/pdf/1906.07538)

