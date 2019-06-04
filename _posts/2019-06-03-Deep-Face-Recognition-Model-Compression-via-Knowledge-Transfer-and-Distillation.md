---
layout: post
title: "Deep Face Recognition Model Compression via Knowledge Transfer and Distillation"
date: 2019-06-03 07:59:53
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Inference Recognition Face_Recognition
author: Jayashree Karlekar, Jiashi Feng, Zi Sian Wong, Sugiri Pranata
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional networks (FCNs) have become de facto tool to achieve very high-level performance for many vision and non-vision tasks in general and face recognition in particular. Such high-level accuracies are normally obtained by very deep networks or their ensemble. However, deploying such high performing models to resource constraint devices or real-time applications is challenging. In this paper, we present a novel model compression approach based on student-teacher paradigm for face recognition applications. The proposed approach consists of training teacher FCN at bigger image resolution while student FCNs are trained at lower image resolutions than that of teacher FCN. We explored three different approaches to train student FCNs: knowledge transfer (KT), knowledge distillation (KD) and their combination. Experimental evaluation on LFW and IJB-C datasets demonstrate comparable improvements in accuracies with these approaches. Training low-resolution student FCNs from higher resolution teacher offer fourfold advantage of accelerated training, accelerated inference, reduced memory requirements and improved accuracies. We evaluated all models on IJB-C dataset and achieved state-of-the-art results on this benchmark. The teacher network and some student networks even achieved Top-1 performance on IJB-C dataset. The proposed approach is simple and hardware friendly, thus enables the deployment of high performing face recognition deep models to resource constraint devices.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00619](http://arxiv.org/abs/1906.00619)

##### PDF
[http://arxiv.org/pdf/1906.00619](http://arxiv.org/pdf/1906.00619)

