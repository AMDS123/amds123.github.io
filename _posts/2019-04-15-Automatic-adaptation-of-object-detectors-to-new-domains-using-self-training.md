---
layout: post
title: "Automatic adaptation of object detectors to new domains using self-training"
date: 2019-04-15 19:46:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Face Tracking Detection
author: Aruni RoyChowdhury, Prithvijit Chakrabarty, Ashish Singh, SouYoung Jin, Huaizu Jiang, Liangliang Cao, Erik Learned-Miller
mathjax: true
---

* content
{:toc}

##### Abstract
This work addresses the unsupervised adaptation of an existing object detector to a new target domain. We assume that a large number of unlabeled videos from this domain are readily available. We automatically obtain labels on the target data by using high-confidence detections from the existing detector, augmented with hard (misclassified) examples acquired by exploiting temporal cues using a tracker. These automatically-obtained labels are then used for re-training the original model. A modified knowledge distillation loss is proposed, and we investigate several ways of assigning soft-labels to the training examples from the target domain. Our approach is empirically evaluated on challenging face and pedestrian detection tasks: a face detector trained on WIDER-Face, which consists of high-quality images crawled from the web, is adapted to a large-scale surveillance data set; a pedestrian detector trained on clear, daytime images from the BDD-100K driving data set is adapted to all other scenarios such as rainy, foggy, night-time. Our results demonstrate the usefulness of incorporating hard examples obtained from tracking, the advantage of using soft-labels via distillation loss versus hard-labels, and show promising performance as a simple method for unsupervised domain adaptation of object detectors, with minimal dependence on hyper-parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07305](http://arxiv.org/abs/1904.07305)

##### PDF
[http://arxiv.org/pdf/1904.07305](http://arxiv.org/pdf/1904.07305)

