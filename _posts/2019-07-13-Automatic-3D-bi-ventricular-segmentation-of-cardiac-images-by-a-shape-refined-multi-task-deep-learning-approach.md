---
layout: post
title: "Automatic 3D bi-ventricular segmentation of cardiac images by a shape-refined multi-task deep learning approach"
date: 2019-07-13 19:39:39
categories: arXiv_AI
tags: arXiv_AI Segmentation Attention CNN Deep_Learning
author: Jinming Duan, Ghalib Bello, Jo Schlemper, Wenjia Bai, Timothy J W Dawes, Carlo Biffi, Antonio de Marvao, Georgia Doumou, Declan P O&#x27;Regan, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning approaches have achieved state-of-the-art performance in cardiac magnetic resonance (CMR) image segmentation. However, most approaches have focused on learning image intensity features for segmentation, whereas the incorporation of anatomical shape priors has received less attention. In this paper, we combine a multi-task deep learning approach with atlas propagation to develop a shape-constrained bi-ventricular segmentation pipeline for short-axis CMR volumetric images. The pipeline first employs a fully convolutional network (FCN) that learns segmentation and landmark localisation tasks simultaneously. The architecture of the proposed FCN uses a 2.5D representation, thus combining the computational advantage of 2D FCNs networks and the capability of addressing 3D spatial consistency without compromising segmentation accuracy. Moreover, the refinement step is designed to explicitly enforce a shape constraint and improve segmentation quality. This step is effective for overcoming image artefacts (e.g. due to different breath-hold positions and large slice thickness), which preclude the creation of anatomically meaningful 3D cardiac shapes. The proposed pipeline is fully automated, due to network's ability to infer landmarks, which are then used downstream in the pipeline to initialise atlas propagation. We validate the pipeline on 1831 healthy subjects and 649 subjects with pulmonary hypertension. Extensive numerical experiments on the two datasets demonstrate that our proposed method is robust and capable of producing accurate, high-resolution and anatomically smooth bi-ventricular 3D models, despite the artefacts in input CMR volumes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.08578](http://arxiv.org/abs/1808.08578)

##### PDF
[http://arxiv.org/pdf/1808.08578](http://arxiv.org/pdf/1808.08578)

