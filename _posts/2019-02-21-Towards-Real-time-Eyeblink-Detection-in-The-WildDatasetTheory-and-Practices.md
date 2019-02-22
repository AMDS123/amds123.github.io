---
layout: post
title: "Towards Real-time Eyeblink Detection in The Wild:Dataset,Theory and Practices"
date: 2019-02-21 07:15:19
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Tracking RNN Detection Recognition
author: Guilei Hu, Yang Xiao, Zhiguo Cao, Lubin Meng, Zhiwen Fang, Joey Tianyi Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Effective and real-time eyeblink detection is of wide-range applications, such as deception detection, drive fatigue detection, face anti-spoofing, etc. Although numerous of efforts have already been paid, most of them focus on addressing the eyeblink detection problem under the constrained indoor conditions with the relative consistent subject and environment setup. Nevertheless, towards the practical applications eyeblink detection in the wild is more required, and of greater challenges. However, to our knowledge this has not been well studied before. In this paper, we shed the light to this research topic. A labelled eyeblink in the wild dataset (i.e., HUST-LEBW) of 673 eyeblink video samples (i.e., 381 positives, and 292 negatives) is first established by us. These samples are captured from the unconstrained movies, with the dramatic variation on human attribute, human pose, illumination condition, imaging configuration, etc. Then, we formulate eyeblink detection task as a spatial-temporal pattern recognition problem. After locating and tracking human eye using SeetaFace engine and KCF tracker respectively, a modified LSTM model able to capture the multi-scale temporal information is proposed to execute eyeblink verification. A feature extraction approach that reveals appearance and motion characteristics simultaneously is also proposed. The experiments on HUST-LEBW reveal the superiority and efficiency of our approach. It also verifies that, the existing eyeblink detection methods cannot achieve satisfactory performance in the wild.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07891](http://arxiv.org/abs/1902.07891)

##### PDF
[http://arxiv.org/pdf/1902.07891](http://arxiv.org/pdf/1902.07891)

