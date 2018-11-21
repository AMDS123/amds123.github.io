---
layout: post
title: "Semi-Supervised Multi-Organ Segmentation via Deep Multi-Planar Co-Training"
date: 2018-11-19 23:24:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention GAN Deep_Learning
author: Yuyin Zhou, Yan Wang, Peng Tang, Song Bai, Wei Shen, Elliot K. Fishman, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In multi-organ segmentation of abdominal CT scans, most existing fully supervised deep learning algorithms require lots of voxel-wise annotations, which are usually difficult, expensive, and slow to obtain. In comparison, massive unlabeled 3D CT volumes are usually easily accessible. Current mainstream works to address the semi-supervised biomedical image segmentation problem are mostly graph-based. By contrast, deep network based semi-supervised learning methods have not drawn much attention in this field. In this work, we propose Deep Multi-Planar Co-Training (DMPCT), whose contributions can be divided into two folds: 1) The deep model is learned in a co-training style which can mine consensus information from multiple planes like the sagittal, coronal, and axial planes; 2) Multi-planar fusion is applied to generate more reliable pseudo-labels, which alleviates the errors occurring in the pseudo-labels and thus can help to train better segmentation networks. Experiments are done on our newly collected large dataset with 100 unlabeled cases as well as 210 labeled cases where 16 anatomical structures are manually annotated by four radiologists and confirmed by a senior expert. The results suggest that DMPCT significantly outperforms the fully supervised method by more than 4% especially when only a small set of annotations is used.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.02586](http://arxiv.org/abs/1804.02586)

##### PDF
[http://arxiv.org/pdf/1804.02586](http://arxiv.org/pdf/1804.02586)

