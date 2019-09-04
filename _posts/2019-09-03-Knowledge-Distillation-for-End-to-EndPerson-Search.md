---
layout: post
title: "Knowledge Distillation for End-to-EndPerson Search"
date: 2019-09-03 10:53:17
categories: arXiv_CV
tags: arXiv_CV Re-identification Object_Detection Knowledge Optimization Detection
author: Bharti Munjal, Fabio Galasso, Sikandar Amin
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce knowledge distillation for end-to-end person search. End-to-End methods are the current state-of-the-art for person search that solve both detection and re-identification jointly. These approaches for joint optimization show their largest drop in performance due to a sub-optimal detector. We propose two distinct approaches for extra supervision of end-to-end person search methods in a teacher-student setting. The first is adopted from state-of-the-art knowledge distillation in object detection. We employ this to supervise the detector of our person search model at various levels using a specialized detector. The second approach is new, simple and yet considerably more effective. This distills knowledge from a teacher re-identification technique via a pre-computed look-up table of ID features. It relaxes the learning of identification features and allows the student to focus on the detection task. This procedure not only helps fixing the sub-optimal detector training in the joint optimization and simultaneously improving the person search, but also closes the performance gap between the teacher and the student for model compression in this case. Overall, we demonstrate significant improvements for two recent state-of-the-art methods using our proposed knowledge distillation approach on two benchmark datasets. Moreover, on the model compression task our approach brings the performance of smaller models on par with the larger models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01058](https://arxiv.org/abs/1909.01058)

##### PDF
[https://arxiv.org/pdf/1909.01058](https://arxiv.org/pdf/1909.01058)

