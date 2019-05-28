---
layout: post
title: "ShrinkTeaNet: Million-scale Lightweight Face Recognition via Shrinking Teacher-Student Networks"
date: 2019-05-25 15:44:40
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN Face Embedding Recognition Face_Recognition
author: Chi Nhan Duong, Khoa Luu, Kha Gia Quach, Ngan Le
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale face recognition in-the-wild has been recently achieved matured performance in many real work applications. However, such systems are built on GPU platforms and mostly deploy heavy deep network architectures. Given a high-performance heavy network as a teacher, this work presents a simple and elegant teacher-student learning paradigm, namely ShrinkTeaNet, to train a portable student network that has significantly fewer parameters and competitive accuracy against the teacher network. Far apart from prior teacher-student frameworks mainly focusing on accuracy and compression ratios in closed-set problems, our proposed teacher-student network is proved to be more robust against open-set problem, i.e. large-scale face recognition. In addition, this work introduces a novel Angular Distillation Loss for distilling the feature direction and the sample distributions of the teacher's hypersphere to its student. Then ShrinkTeaNet framework can efficiently guide the student's learning process with the teacher's knowledge presented in both intermediate and last stages of the feature embedding. Evaluations on LFW, CFP-FP, AgeDB, IJB-B and IJB-C Janus, and MegaFace with one million distractors have demonstrated the efficiency of the proposed approach to learn robust student networks which have satisfying accuracy and compact sizes. Our ShrinkTeaNet is able to support the light-weight architecture achieving high performance with 99.77% on LFW and 95.64% on large-scale Megaface protocols.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10620](http://arxiv.org/abs/1905.10620)

##### PDF
[http://arxiv.org/pdf/1905.10620](http://arxiv.org/pdf/1905.10620)

