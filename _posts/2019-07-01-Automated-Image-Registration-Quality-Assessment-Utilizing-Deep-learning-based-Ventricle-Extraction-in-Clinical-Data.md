---
layout: post
title: "Automated Image Registration Quality Assessment Utilizing Deep-learning based Ventricle Extraction in Clinical Data"
date: 2019-07-01 12:22:39
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Florian Dubost, Marleen de Bruijne, Marco Nardin, Adrian V. Dalca, Kathleen L. Donahue, Anne-Katrin Giese, Mark R. Etherton, Ona Wu, Marius de Groot, Wiro Niessen, Meike Vernooij, Natalia S. Rost, Markus D. Schirmer
mathjax: true
---

* content
{:toc}

##### Abstract
Registration is a core component of many imaging pipelines. In case of clinical scans, with lower resolution and sometimes substantial motion artifacts, registration can produce poor results. Visual assessment of registration quality in large clinical datasets is inefficient. In this work, we propose to automatically assess the quality of registration to an atlas in clinical FLAIR MRI scans of the brain. The method consists of automatically segmenting the ventricles of a given scan using a neural network, and comparing the segmentation to the atlas' ventricles propagated to image space. We used the proposed method to improve clinical image registration to a general atlas by computing multiple registrations and then selecting the registration that yielded the highest ventricle overlap. Methods were evaluated in a single-site dataset of more than 1000 scans, as well as a multi-center dataset comprising 142 clinical scans from 12 sites. The automated ventricle segmentation reached a Dice coefficient with manual annotations of 0.89 in the single-site dataset, and 0.83 in the multi-center dataset. Registration via age-specific atlases could improve ventricle overlap compared to a direct registration to the general atlas (Dice similarity coefficient increase up to 0.15). Experiments also showed that selecting scans with the registration quality assessment method could improve the quality of average maps of white matter hyperintensity burden, instead of using all scans for the computation of the white matter hyperintensity map. In this work, we demonstrated the utility of an automated tool for assessing image registration quality in clinical scans. This image quality assessment step could ultimately assist in the translation of automated neuroimaging pipelines to the clinic.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00695](http://arxiv.org/abs/1907.00695)

##### PDF
[http://arxiv.org/pdf/1907.00695](http://arxiv.org/pdf/1907.00695)

