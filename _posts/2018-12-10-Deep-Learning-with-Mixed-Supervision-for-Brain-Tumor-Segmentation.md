---
layout: post
title: "Deep Learning with Mixed Supervision for Brain Tumor Segmentation"
date: 2018-12-10 16:03:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning
author: Pawel Mlynarski, Herv&#xe9; Delingette, Antonio Criminisi, Nicholas Ayache
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the current state-of-the-art methods for tumor segmentation are based on machine learning models trained on manually segmented images. This type of training data is particularly costly, as manual delineation of tumors is not only time-consuming but also requires medical expertise. On the other hand, images with a provided global label (indicating presence or absence of a tumor) are less informative but can be obtained at a substantially lower cost. In this paper, we propose to use both types of training data (fully-annotated and weakly-annotated) to train a deep learning model for segmentation. The idea of our approach is to extend segmentation networks with an additional branch performing image-level classification. The model is jointly trained for segmentation and classification tasks in order to exploit information contained in weakly-annotated images while preventing the network to learn features which are irrelevant for the segmentation task. We evaluate our method on the challenging task of brain tumor segmentation in Magnetic Resonance images from BRATS 2018 challenge. We show that the proposed approach provides a significant improvement of segmentation performance compared to the standard supervised learning. The observed improvement is proportional to the ratio between weakly-annotated and fully-annotated images available for training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04571](http://arxiv.org/abs/1812.04571)

##### PDF
[http://arxiv.org/pdf/1812.04571](http://arxiv.org/pdf/1812.04571)

