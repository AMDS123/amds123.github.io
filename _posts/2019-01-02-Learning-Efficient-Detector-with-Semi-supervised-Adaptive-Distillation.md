---
layout: post
title: "Learning Efficient Detector with Semi-supervised Adaptive Distillation"
date: 2019-01-02 14:03:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Attention Image_Classification Classification Prediction Detection
author: Shitao Tang, Litong Feng, Wenqi Shao, Zhanghui Kuang, Wei Zhang, Yimin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge Distillation (KD) has been used in image classification for model compression. However, rare studies apply this technology on single-stage object detectors. Focal loss shows that the accumulated errors of easily-classified samples dominate the overall loss in the training process. This problem is also encountered when applying KD in the detection task. For KD, the teacher-defined hard samples are far more important than any others. We propose ADL to address this issue by adaptively mimicking the teacher's logits, with more attention paid on two types of hard samples: hard-to-learn samples predicted by teacher with low certainty and hard-to-mimic samples with a large gap between the teacher's and the student's prediction. ADL enlarges the distillation loss for hard-to-learn and hard-to-mimic samples and reduces distillation loss for the dominant easy samples, enabling distillation to work on the single-stage detector first time, even if the student and the teacher are identical. Besides, ADL is effective in both the supervised setting and the semi-supervised setting, even when the labeled data and unlabeled data are from different distributions. For distillation on unlabeled data, ADL achieves better performance than existing data distillation which simply utilizes hard targets, making the student detector surpass its teacher. On the COCO database, semi-supervised adaptive distillation (SAD) makes a student detector with a backbone of ResNet-50 surpasses its teacher with a backbone of ResNet-101, while the student has half of the teacher's computation complexity. The code is avaiable at this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.00366](https://arxiv.org/abs/1901.00366)

##### PDF
[https://arxiv.org/pdf/1901.00366](https://arxiv.org/pdf/1901.00366)

