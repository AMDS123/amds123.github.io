---
layout: post
title: "Anatomical Priors in Convolutional Networks for Unsupervised Biomedical Segmentation"
date: 2019-03-07 19:51:03
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Adrian V. Dalca, John Guttag, Mert R. Sabuncu
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of segmenting a biomedical image into anatomical regions of interest. We specifically address the frequent scenario where we have no paired training data that contains images and their manual segmentations. Instead, we employ unpaired segmentation images to build an anatomical prior. Critically these segmentations can be derived from imaging data from a different dataset and imaging modality than the current task. We introduce a generative probabilistic model that employs the learned prior through a convolutional neural network to compute segmentations in an unsupervised setting. We conducted an empirical analysis of the proposed approach in the context of structural brain MRI segmentation, using a multi-study dataset of more than 14,000 scans. Our results show that an anatomical prior can enable fast unsupervised segmentation which is typically not possible using standard convolutional networks. The integration of anatomical priors can facilitate CNN-based anatomical segmentation in a range of novel clinical problems, where few or no annotations are available and thus standard networks are not trainable. The code is freely available at <a href="http://github.com/adalca/neuron.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03148](http://arxiv.org/abs/1903.03148)

##### PDF
[http://arxiv.org/pdf/1903.03148](http://arxiv.org/pdf/1903.03148)

