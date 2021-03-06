---
layout: post
title: "Weakly Supervised Estimation of Shadow Confidence Maps in Fetal Ultrasound Imaging"
date: 2019-05-06 17:03:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Image_Classification Inference Classification Quantitative Relation
author: Qingjie Meng, Matthew Sinclair, Veronika Zimmer, Benjamin Hou, Martin Rajchl, Nicolas Toussaint, Ozan Oktay, Jo Schlemper, Alberto Gomez, James Housden, Jacqueline Matthew, Daniel Rueckert, Julia Schnabel, Bernhard Kainz
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting acoustic shadows in ultrasound images is important in many clinical and engineering applications. Real-time feedback of acoustic shadows can guide sonographers to a standardized diagnostic viewing plane with minimal artifacts and can provide additional information for other automatic image analysis algorithms. However, automatically detecting shadow regions using learning-based algorithms is challenging because pixel-wise ground truth annotation of acoustic shadows is subjective and time consuming. In this paper we propose a weakly supervised method for automatic confidence estimation of acoustic shadow regions. Our method is able to generate a dense shadow-focused confidence map. In our method, a shadow-seg module is built to learn general shadow features for shadow segmentation, based on global image-level annotations as well as a small number of coarse pixel-wise shadow annotations. A transfer function is introduced to extend the obtained binary shadow segmentation to a reference confidence map. Additionally, a confidence estimation network is proposed to learn the mapping between input images and the reference confidence maps. This network is able to predict shadow confidence maps directly from input images during inference. We use evaluation metrics such as DICE, inter-class correlation and etc. to verify the effectiveness of our method. Our method is more consistent than human annotation, and outperforms the state-of-the-art quantitatively in shadow segmentation and qualitatively in confidence estimation of shadow regions. We further demonstrate the applicability of our method by integrating shadow confidence maps into tasks such as ultrasound image classification, multi-view image fusion and automated biometric measurements.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08164](http://arxiv.org/abs/1811.08164)

##### PDF
[http://arxiv.org/pdf/1811.08164](http://arxiv.org/pdf/1811.08164)

