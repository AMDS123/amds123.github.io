---
layout: post
title: "Joint inference on structural and diffusion MRI for sequence-adaptive Bayesian segmentation of thalamic nuclei with probabilistic atlases"
date: 2019-03-11 15:11:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Juan Eugenio Iglesias, Koen Van Leemput, Polina Golland, Anastasia Yendiki
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of structural and diffusion MRI (sMRI/dMRI) is usually performed independently in neuroimaging pipelines. However, some brain structures (e.g., globus pallidus, thalamus and its nuclei) can be extracted more accurately by fusing the two modalities. Following the framework of Bayesian segmentation with probabilistic atlases and unsupervised appearance modeling, we present here a novel algorithm to jointly segment multi-modal sMRI/dMRI data. We propose a hierarchical likelihood term for the dMRI defined on the unit ball, which combines the Beta and Dimroth-Scheidegger-Watson distributions to model the data at each voxel. This term is integrated with a mixture of Gaussians for the sMRI data, such that the resulting joint unsupervised likelihood enables the analysis of multi-modal scans acquired with any type of MRI contrast, b-values, or number of directions, which enables wide applicability. We also propose an inference algorithm to estimate the maximum-a-posteriori model parameters from input images, and to compute the most likely segmentation. Using a recently published atlas derived from histology, we apply our method to thalamic nuclei segmentation on two datasets: HCP (state of the art) and ADNI (legacy) - producing lower sample sizes than Bayesian segmentation with sMRI alone.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.04352](https://arxiv.org/abs/1903.04352)

##### PDF
[https://arxiv.org/pdf/1903.04352](https://arxiv.org/pdf/1903.04352)

