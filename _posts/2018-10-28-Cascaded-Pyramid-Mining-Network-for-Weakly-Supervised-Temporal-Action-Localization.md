---
layout: post
title: "Cascaded Pyramid Mining Network for Weakly Supervised Temporal Action Localization"
date: 2018-10-28 11:10:33
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention Weakly_Supervised Video_Classification Classification Detection
author: Haisheng Su, Xu Zhao, Tianwei Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised temporal action localization, which aims at temporally locating action instances in untrimmed videos using only video-level class labels during training, is an important yet challenging problem in video analysis. Many current methods adopt the "localization by classification" framework: first do video classification, then locate temporal area contributing to the results most. However, this framework fails to locate the entire action instances and gives little consideration to the local context. In this paper, we present a novel architecture called Cascaded Pyramid Mining Network (CPMN) to address these issues using two effective modules. First, to discover the entire temporal interval of specific action, we design a two-stage cascaded module with proposed Online Adversarial Erasing (OAE) mechanism, where new and complementary regions are mined through feeding the erased feature maps of discovered regions back to the system. Second, to exploit hierarchical contextual information in videos and reduce missing detections, we design a pyramid module which produces a scale-invariant attention map through combining the feature maps from different levels. Final, we aggregate the results of two modules to perform action localization via locating high score areas in temporal Class Activation Sequence (CAS). Extensive experiments conducted on THUMOS14 and ActivityNet-1.3 datasets demonstrate the effectiveness of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11794](http://arxiv.org/abs/1810.11794)

##### PDF
[http://arxiv.org/pdf/1810.11794](http://arxiv.org/pdf/1810.11794)

