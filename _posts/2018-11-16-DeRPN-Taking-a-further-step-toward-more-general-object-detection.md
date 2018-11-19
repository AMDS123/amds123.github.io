---
layout: post
title: "DeRPN: Taking a further step toward more general object detection"
date: 2018-11-16 08:25:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Detection
author: Lele Xie, Yuliang Liu, Lianwen Jin, Zecheng Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Most current detection methods have adopted anchor boxes as regression references. However, the detection performance is sensitive to the setting of the anchor boxes. A proper setting of anchor boxes may vary significantly across different datasets, which severely limits the universality of the detectors. To improve the adaptivity of the detectors, in this paper, we present a novel dimension-decomposition region proposal network (DeRPN) that can perfectly displace the traditional Region Proposal Network (RPN). DeRPN utilizes an anchor string mechanism to independently match object widths and heights, which is conducive to treating variant object shapes. In addition, a novel scale-sensitive loss is designed to address the imbalanced loss computations of different scaled objects, which can avoid the small objects being overwhelmed by larger ones. Comprehensive experiments conducted on both general object detection datasets (Pascal VOC 2007, 2012 and MS COCO) and scene text detection datasets (ICDAR 2013 and COCO-Text) all prove that our DeRPN can significantly outperform RPN. It is worth mentioning that the proposed DeRPN can be employed directly on different models, tasks, and datasets without any modifications of hyperparameters or specialized optimization, which further demonstrates its adaptivity. The code will be released at https://github.com/HCIILAB/DeRPN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06700](http://arxiv.org/abs/1811.06700)

##### PDF
[http://arxiv.org/pdf/1811.06700](http://arxiv.org/pdf/1811.06700)

