---
layout: post
title: "LoANs: Weakly Supervised Object Detection with Localizer Assessor Networks"
date: 2018-11-14 13:45:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection Recognition
author: Christian Bartz, Haojin Yang, Joseph Bethge, Christoph Meinel
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep neural networks have achieved remarkable performance on the task of object detection and recognition. The reason for this success is mainly grounded in the availability of large scale, fully annotated datasets, but the creation of such a dataset is a complicated and costly task. In this paper, we propose a novel method for weakly supervised object detection that simplifies the process of gathering data for training an object detector. We train an ensemble of two models that work together in a student-teacher fashion. Our student (localizer) is a model that learns to localize an object, the teacher (assessor) assesses the quality of the localization and provides feedback to the student. The student uses this feedback to learn how to localize objects and is thus entirely supervised by the teacher, as we are using no labels for training the localizer. In our experiments, we show that our model is very robust to noise and reaches competitive performance compared to a state-of-the-art fully supervised approach. We also show the simplicity of creating a new dataset, based on a few videos (e.g. downloaded from YouTube) and artificially generated data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05773](http://arxiv.org/abs/1811.05773)

##### PDF
[http://arxiv.org/pdf/1811.05773](http://arxiv.org/pdf/1811.05773)

