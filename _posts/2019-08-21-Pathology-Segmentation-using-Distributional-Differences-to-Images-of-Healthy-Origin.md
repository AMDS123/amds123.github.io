---
layout: post
title: "Pathology Segmentation using Distributional Differences to Images of Healthy Origin"
date: 2019-08-21 08:28:24
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Semantic_Segmentation Quantitative
author: Simon Andermatt, Antal Horv&#xe1;th, Simon Pezold, Philippe Cattin
mathjax: true
---

* content
{:toc}

##### Abstract
Fully supervised segmentation methods require a large training cohort of already segmented images, providing information at the pixel level of each image. We present a method to automatically segment and model pathologies in medical images, trained solely on data labelled on the image level as either healthy or containing a visual defect. We base our method on CycleGAN, an image-to-image translation technique, to translate images between the domains of healthy and pathological images. We extend the core idea with two key contributions. Implementing the generators as residual generators allows us to explicitly model the segmentation of the pathology. Realizing the translation from the healthy to the pathological domain using a variational autoencoder allows us to specify one representation of the pathology, as this transformation is otherwise not unique. Our model hence not only allows us to create pixelwise semantic segmentations, it is also able to create inpaintings for the segmentations to render the pathological image healthy. Furthermore, we can draw new unseen pathology samples from this model based on the distribution in the data. We show quantitatively, that our method is able to segment pathologies with a surprising accuracy being only slightly inferior to a state-of-the-art fully supervised method, although the latter has per-pixel rather than per-image training information. Moreover, we show qualitative results of both the segmentations and inpaintings. Our findings motivate further research into weakly-supervised segmentation using image level annotations, allowing for faster and cheaper acquisition of training data without a large sacrifice in segmentation accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10344](http://arxiv.org/abs/1805.10344)

##### PDF
[http://arxiv.org/pdf/1805.10344](http://arxiv.org/pdf/1805.10344)

