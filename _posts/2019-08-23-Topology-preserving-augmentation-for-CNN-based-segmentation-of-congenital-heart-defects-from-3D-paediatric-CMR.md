---
layout: post
title: "Topology-preserving augmentation for CNN-based segmentation of congenital heart defects from 3D paediatric CMR"
date: 2019-08-23 15:34:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Face
author: Nick Byrne, James R. Clough, Isra Valverde, Giovanni Montana, Andrew P. King
mathjax: true
---

* content
{:toc}

##### Abstract
Patient-specific 3D printing of congenital heart anatomy demands an accurate segmentation of the thin tissue interfaces which characterise these diagnoses. Even when a label set has a high spatial overlap with the ground truth, inaccurate delineation of these interfaces can result in topological errors. These compromise the clinical utility of such models due to the anomalous appearance of defects. CNNs have achieved state-of-the-art performance in segmentation tasks. Whilst data augmentation has often played an important role, we show that conventional image resampling schemes used therein can introduce topological changes in the ground truth labelling of augmented samples. We present a novel pipeline to correct for these changes, using a fast-marching algorithm to enforce the topology of the ground truth labels within their augmented representations. In so doing, we invoke the idea of cardiac contiguous topology to describe an arbitrary combination of congenital heart defects and develop an associated, clinically meaningful metric to measure the topological correctness of segmentations. In a series of five-fold cross-validations, we demonstrate the performance gain produced by this pipeline and the relevance of topological considerations to the segmentation of congenital heart defects. We speculate as to the applicability of this approach to any segmentation task involving morphologically complex targets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08870](http://arxiv.org/abs/1908.08870)

##### PDF
[http://arxiv.org/pdf/1908.08870](http://arxiv.org/pdf/1908.08870)

