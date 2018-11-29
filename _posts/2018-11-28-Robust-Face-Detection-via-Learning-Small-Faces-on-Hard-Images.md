---
layout: post
title: "Robust Face Detection via Learning Small Faces on Hard Images"
date: 2018-11-28 16:43:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: Zhishuai Zhang, Wei Shen, Siyuan Qiao, Yan Wang, Bo Wang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Recent anchor-based deep face detectors have achieved promising performance, but they are still struggling to detect hard faces, such as small, blurred and partially occluded faces. A reason is that they treat all images and faces equally, without putting more effort on hard ones; however, many training images only contain easy faces, which are less helpful to achieve better performance on hard images. In this paper, we propose that the robustness of a face detector against hard faces can be improved by learning small faces on hard images. Our intuitions are (1) hard images are the images which contain at least one hard face, thus they facilitate training robust face detectors; (2) most hard faces are small faces and other types of hard faces can be easily converted to small faces by shrinking. We build an anchor-based deep face detector, which only output a single feature map with small anchors, to specifically learn small faces and train it by a novel hard image mining strategy. Extensive experiments have been conducted on WIDER FACE, FDDB, Pascal Faces, and AFW datasets to show the effectiveness of our method. Our method achieves APs of 95.7, 94.9 and 89.7 on easy, medium and hard WIDER FACE val dataset respectively, which surpass the previous state-of-the-arts, especially on the hard subset. Code and model are available at https://github.com/bairdzhang/smallhardface.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11662](http://arxiv.org/abs/1811.11662)

##### PDF
[http://arxiv.org/pdf/1811.11662](http://arxiv.org/pdf/1811.11662)

