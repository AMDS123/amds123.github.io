---
layout: post
title: "Clinically Accurate Chest X-Ray Report Generation"
date: 2019-04-04 16:04:30
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Guanxiong Liu, Tzu-Ming Harry Hsu, Matthew McDermott, Willie Boag, Wei-Hung Weng, Peter Szolovits, Marzyeh Ghassemi
mathjax: true
---

* content
{:toc}

##### Abstract
The automatic generation of radiology reports given medical radiographs has significant potential to operationally and clinically improve patient care. A number of prior works have focused on this problem, employing advanced methods from computer vision and natural language generation to produce readable reports. However, these works often fail to account for the particular nuances of the radiology domain, and, in particular, the critical importance of clinical accuracy in the resulting generated reports. In this work, we present a domain-aware automatic chest X-Ray radiology report generation system which first predicts what topics will be discussed in the report, then conditionally generates sentences corresponding to these topics. The resulting system is fine-tuned using reinforcement learning, considering both readability and clinical accuracy, as assessed by the proposed Clinically Coherent Reward. We verify this system on two datasets, Open-I and MIMIC-CXR, and demonstrate that our model offers marked improvements on both language generation metrics and CheXpert assessed accuracy over a variety of competitive baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02633](http://arxiv.org/abs/1904.02633)

##### PDF
[http://arxiv.org/pdf/1904.02633](http://arxiv.org/pdf/1904.02633)

