---
layout: post
title: "DUAL-GLOW: Conditional Flow-Based Generative Model for Modality Transfer"
date: 2019-08-21 18:14:09
categories: arXiv_CV
tags: arXiv_CV Quantitative Relation
author: Haoliang Sun, Ronak Mehta, Hao H. Zhou, Zhichun Huang, Sterling C. Johnson, Vivek Prabhakaran, Vikas Singh
mathjax: true
---

* content
{:toc}

##### Abstract
Positron emission tomography (PET) imaging is an imaging modality for diagnosing a number of neurological diseases. In contrast to Magnetic Resonance Imaging (MRI), PET is costly and involves injecting a radioactive substance into the patient. Motivated by developments in modality transfer in vision, we study the generation of certain types of PET images from MRI data. We derive new flow-based generative models which we show perform well in this small sample size regime (much smaller than dataset sizes available in standard vision tasks). Our formulation, DUAL-GLOW, is based on two invertible networks and a relation network that maps the latent spaces to each other. We discuss how given the prior distribution, learning the conditional distribution of PET given the MRI image reduces to obtaining the conditional distribution between the two latent codes w.r.t. the two image types. We also extend our framework to leverage 'side' information (or attributes) when available. By controlling the PET generation through 'conditioning' on age, our model is also able to capture brain FDG-PET (hypometabolism) changes, as a function of age. We present experiments on the Alzheimers Disease Neuroimaging Initiative (ADNI) dataset with 826 subjects, and obtain good performance in PET image synthesis, qualitatively and quantitatively better than recent works.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08074](https://arxiv.org/abs/1908.08074)

##### PDF
[https://arxiv.org/pdf/1908.08074](https://arxiv.org/pdf/1908.08074)

