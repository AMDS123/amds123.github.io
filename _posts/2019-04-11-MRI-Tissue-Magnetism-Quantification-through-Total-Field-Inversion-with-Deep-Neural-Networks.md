---
layout: post
title: "MRI Tissue Magnetism Quantification through Total Field Inversion with Deep Neural Networks"
date: 2019-04-11 20:18:27
categories: arXiv_AI
tags: arXiv_AI Quantitative Relation
author: Juan Liu, Kevin M. Koch
mathjax: true
---

* content
{:toc}

##### Abstract
Quantitative susceptibility mapping (QSM) utilizes MRI signal phase to infer estimates of local tissue magnetism (magnetic susceptibility), which has been shown useful to provide novel image contrast and as biomarkers of abnormal tissue. QSM requires addressing a challenging post-processing problem: filtering of image phase estimates and inversion of the phase to susceptibility relationship. A wide variety of quantification errors, robustness limitations, and artifacts plague QSM algorithms. To overcome these limitations, a robust deep-learning-based single-step QSM reconstruction approach is proposed and demonstrated. This neural network was trained using magnetostatic physics simulations based on in-vivo data sources. Random perturbations were added to the physics simulations to provide sufficient input-label pairs for the training purposes. The network was quantitatively tested using gold-standard in-silico labeled datasets against established QSM total field inversion approaches. In addition, the algorithm was applied to susceptibility-weighted imaging (SWI) data collected on a cohort of clinical subjects with brain hemmhorage. When quantitatively compared against gold-standard in-silico labels, the proposed algorithm outperformed the existing comparable approaches. High quality QSM were consistently estimated from clinical susceptibility-weighted data on 100 subjects without any noticeable inversion failures. The proposed approach was able to robustly generate high quality QSM with improved accuracy in in-silico gold-standard experiments. QSM produced by the proposed method can be generated in real-time on existing MRI scanner platforms and provide enhanced visualization and quantification of magnetism-based tissue contrasts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07105](http://arxiv.org/abs/1904.07105)

##### PDF
[http://arxiv.org/pdf/1904.07105](http://arxiv.org/pdf/1904.07105)

