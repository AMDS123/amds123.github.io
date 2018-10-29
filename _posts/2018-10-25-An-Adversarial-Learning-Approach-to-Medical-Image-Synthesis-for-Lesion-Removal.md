---
layout: post
title: "An Adversarial Learning Approach to Medical Image Synthesis for Lesion Removal"
date: 2018-10-25 12:57:31
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Segmentation GAN Classification
author: Liyan Sun, Jiexiang Wang, Xinghao Ding, Yue Huang, John Paisley
mathjax: true
---

* content
{:toc}

##### Abstract
The analysis of lesion within medical image data is desirable for efficient disease diagnosis, treatment and prognosis. The common lesion analysis tasks like segmentation and classification are mainly based on supervised learning with well-paired image-level or voxel-level labels. However, labeling the lesion in medical images is laborious requiring highly specialized knowledge. Inspired by the fact that radiologists make diagnoses based on expert knowledge on "healthiness" and "unhealthiness" developed from extensive experience, we propose an medical image synthesis model named abnormal-to-normal translation generative adversarial network (ANT-GAN) to predict a normal-looking medical image based on its abnormal-looking counterpart without the need of paired data for training. Unlike typical GANs, whose aim is to generate realistic samples with variations, our more restrictive model aims at producing the underlying normal-looking image corresponding to an image containing lesions, and thus requires a specialized design. With an ability to segment normal from abnormal tissue, our model is able to generate a highly realistic lesion-free medical image based on its true lesion-containing counterpart. Being able to provide a "normal" version of a medical image (possibly the same image if there is no illness) is not only an intriguing topic, but also can serve as a pre-processing and provide useful side information for medical imaging tasks like lesion segmentation or classification validated by our experiments.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10850](https://arxiv.org/abs/1810.10850)

##### PDF
[https://arxiv.org/pdf/1810.10850](https://arxiv.org/pdf/1810.10850)

