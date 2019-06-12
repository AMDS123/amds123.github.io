---
layout: post
title: "Automatic brain tissue segmentation in fetal MRI using convolutional neural networks"
date: 2019-06-11 17:28:25
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN
author: N. Khalili, N. Lessmann, E. Turk, N. Claessens, R. de Heus, T. Kolk, M.A. Viergever, M.J.N.L. Benders, I. Isgum
mathjax: true
---

* content
{:toc}

##### Abstract
MR images of fetuses allow clinicians to detect brain abnormalities in an early stage of development. The cornerstone of volumetric and morphologic analysis in fetal MRI is segmentation of the fetal brain into different tissue classes. Manual segmentation is cumbersome and time consuming, hence automatic segmentation could substantially simplify the procedure. However, automatic brain tissue segmentation in these scans is challenging owing to artifacts including intensity inhomogeneity, caused in particular by spontaneous fetal movements during the scan. Unlike methods that estimate the bias field to remove intensity inhomogeneity as a preprocessing step to segmentation, we propose to perform segmentation using a convolutional neural network that exploits images with synthetically introduced intensity inhomogeneity as data augmentation. The method first uses a CNN to extract the intracranial volume. Thereafter, another CNN with the same architecture is employed to segment the extracted volume into seven brain tissue classes: cerebellum, basal ganglia and thalami, ventricular cerebrospinal fluid, white matter, brain stem, cortical gray matter and extracerebral cerebrospinal fluid. To make the method applicable to slices showing intensity inhomogeneity artifacts, the training data was augmented by applying a combination of linear gradients with random offsets and orientations to image slices without artifacts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04713](http://arxiv.org/abs/1906.04713)

##### PDF
[http://arxiv.org/pdf/1906.04713](http://arxiv.org/pdf/1906.04713)

