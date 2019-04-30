---
layout: post
title: "Fast Infant MRI Skullstripping with Multiview 2D Convolutional Neural Networks"
date: 2019-04-27 03:33:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Amod Jog, P. Ellen Grant, Joseph L. Jacobson, Andre van der Kouwe, Ernesta M. Meintjes, Bruce Fischl, Lilla Z&#xf6;llei
mathjax: true
---

* content
{:toc}

##### Abstract
Skullstripping is defined as the task of segmenting brain tissue from a full head magnetic resonance image~(MRI). It is a critical component in neuroimage processing pipelines. Downstream deformable registration and whole brain segmentation performance is highly dependent on accurate skullstripping. Skullstripping is an especially challenging task for infant~(age range 0--18 months) head MRI images due to the significant size and shape variability of the head and the brain in that age range. Infant brain tissue development also changes the $T_1$-weighted image contrast over time, making consistent skullstripping a difficult task. Existing tools for adult brain MRI skullstripping are ill equipped to handle these variations and a specialized infant MRI skullstripping algorithm is necessary. In this paper, we describe a supervised skullstripping algorithm that utilizes three trained fully convolutional neural networks~(CNN), each of which segments 2D $T_1$-weighted slices in axial, coronal, and sagittal views respectively. The three probabilistic segmentations in the three views are linearly fused and thresholded to produce a final brain mask. We compared our method to existing adult and infant skullstripping algorithms and showed significant improvement based on Dice overlap metric~(average Dice of 0.97) with a manually labeled ground truth data set. Label fusion experiments on multiple, unlabeled data sets show that our method is consistent and has fewer failure modes. In addition, our method is computationally very fast with a run time of 30 seconds per image on NVidia P40/P100/Quadro 4000 GPUs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12101](http://arxiv.org/abs/1904.12101)

##### PDF
[http://arxiv.org/pdf/1904.12101](http://arxiv.org/pdf/1904.12101)

