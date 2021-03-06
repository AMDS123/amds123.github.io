---
layout: post
title: "Joint segmentation and classification of retinal arteries/veins from fundus images"
date: 2019-03-04 16:17:33
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Deep_Learning
author: Fantin Girard, Conrad Kavalec, Farida Cheriet
mathjax: true
---

* content
{:toc}

##### Abstract
Objective Automatic artery/vein (A/V) segmentation from fundus images is required to track blood vessel changes occurring with many pathologies including retinopathy and cardiovascular pathologies. One of the clinical measures that quantifies vessel changes is the arterio-venous ratio (AVR) which represents the ratio between artery and vein diameters. This measure significantly depends on the accuracy of vessel segmentation and classification into arteries and veins. This paper proposes a fast, novel method for semantic A/V segmentation combining deep learning and graph propagation. 
 Methods A convolutional neural network (CNN) is proposed to jointly segment and classify vessels into arteries and veins. The initial CNN labeling is propagated through a graph representation of the retinal vasculature, whose nodes are defined as the vessel branches and edges are weighted by the cost of linking pairs of branches. To efficiently propagate the labels, the graph is simplified into its minimum spanning tree. 
 Results The method achieves an accuracy of 94.8% for vessels segmentation. The A/V classification achieves a specificity of 92.9% with a sensitivity of 93.7% on the CT-DRIVE database compared to the state-of-the-art-specificity and sensitivity, both of 91.7%. 
 Conclusion The results show that our method outperforms the leading previous works on a public dataset for A/V classification and is by far the fastest. 
 Significance The proposed global AVR calculated on the whole fundus image using our automatic A/V segmentation method can better track vessel changes associated to diabetic retinopathy than the standard local AVR calculated only around the optic disc.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01330](http://arxiv.org/abs/1903.01330)

##### PDF
[http://arxiv.org/pdf/1903.01330](http://arxiv.org/pdf/1903.01330)

