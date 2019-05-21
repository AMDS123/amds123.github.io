---
layout: post
title: "Semantic Foggy Scene Understanding with Synthetic Data"
date: 2019-05-17 18:55:04
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Attention CNN Semantic_Segmentation Detection
author: Christos Sakaridis, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
This work addresses the problem of semantic foggy scene understanding (SFSU). Although extensive research has been performed on image dehazing and on semantic scene understanding with clear-weather images, little attention has been paid to SFSU. Due to the difficulty of collecting and annotating foggy images, we choose to generate synthetic fog on real images that depict clear-weather outdoor scenes, and then leverage these partially synthetic data for SFSU by employing state-of-the-art convolutional neural networks (CNN). In particular, a complete pipeline to add synthetic fog to real, clear-weather images using incomplete depth information is developed. We apply our fog synthesis on the Cityscapes dataset and generate Foggy Cityscapes with 20550 images. SFSU is tackled in two ways: 1) with typical supervised learning, and 2) with a novel type of semi-supervised learning, which combines 1) with an unsupervised supervision transfer from clear-weather images to their synthetic foggy counterparts. In addition, we carefully study the usefulness of image dehazing for SFSU. For evaluation, we present Foggy Driving, a dataset with 101 real-world images depicting foggy driving scenes, which come with ground truth annotations for semantic segmentation and object detection. Extensive experiments show that 1) supervised learning with our synthetic data significantly improves the performance of state-of-the-art CNN for SFSU on Foggy Driving; 2) our semi-supervised learning strategy further improves performance; and 3) image dehazing marginally advances SFSU with our learning strategy. The datasets, models and code are made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1708.07819](http://arxiv.org/abs/1708.07819)

##### PDF
[http://arxiv.org/pdf/1708.07819](http://arxiv.org/pdf/1708.07819)

