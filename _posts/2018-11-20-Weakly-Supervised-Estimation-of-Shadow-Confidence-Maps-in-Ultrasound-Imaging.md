---
layout: post
title: "Weakly Supervised Estimation of Shadow Confidence Maps in Ultrasound Imaging"
date: 2018-11-20 10:20:39
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Image_Classification Inference Classification Quantitative Relation
author: Qingjie Meng, Matthew Sinclair, Veronika Zimmer, Benjamin Hou, Martin Rajchl, Nicolas Toussaint, Alberto Gomez, James Housden, Jacqueline Matthew, Daniel Rueckert, Julia Schnabel, Bernhard Kainz
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting acoustic shadows in ultrasound images is important in many clinical and engineering applications. Real-time feedback of acoustic shadows can guide sonographers to a standardized diagnostic viewing plane with minimal artifacts and can provide additional information for other automatic image analysis algorithms. However, automatically detecting shadow regions is challenging because pixel-wise annotation of acoustic shadows is subjective and time consuming. In this paper we propose a weakly supervised method for automatic confidence estimation of acoustic shadow regions, which is able to generate a dense shadow-focused confidence map. During training, a multi-task module for shadow segmentation is built to learn general shadow features according based image-level annotations as well as a small number of coarse pixel-wise shadow annotations. A transfer function is then established to extend the binary shadow segmentation to a reference confidence map. In addition, a confidence estimation network is proposed to learn the mapping between input images and the reference confidence maps. This confidence estimation network is able to predict shadow confidence maps directly from input images during inference. We evaluate DICE, soft DICE, recall, precision, mean squared error and inter-class correlation to verify the effectiveness of our method. Our method outperforms the state-of-the-art qualitatively and quantitatively. We further demonstrate the applicability of our method by integrating shadow confidence maps into tasks such as ultrasound image classification, multi-view image fusion and automated biometric measurements.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08164](http://arxiv.org/abs/1811.08164)

##### PDF
[http://arxiv.org/pdf/1811.08164](http://arxiv.org/pdf/1811.08164)

