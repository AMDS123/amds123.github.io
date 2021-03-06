---
layout: post
title: "Learning Rich Representations For Structured Visual Prediction Tasks"
date: 2019-08-30 16:18:26
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Segmentation Weakly_Supervised Semantic_Segmentation Inference Classification Prediction
author: Mohammadreza Mostajabi
mathjax: true
---

* content
{:toc}

##### Abstract
We describe an approach to learning rich representations for images, that enables simple and effective predictors in a range of vision tasks involving spatially structured maps. Our key idea is to map small image elements to feature representations extracted from a sequence of nested regions of increasing spatial extent. These regions are obtained by "zooming out" from the pixel/superpixel all the way to scene-level resolution, and hence we call these zoom-out features. Applied to semantic segmentation and other structured prediction tasks, our approach exploits statistical structure in the image and in the label space without setting up explicit structured prediction mechanisms, and thus avoids complex and expensive inference. Instead image elements are classified by a feedforward multilayer network with skip-layer connections spanning the zoom-out levels. When used in conjunction with modern neural architectures such as ResNet, DenseNet and NASNet (to which it is complementary) our approach achieves competitive accuracy on segmentation benchmarks. 
 In addition, we propose an approach for learning category-level semantic segmentation purely from image-level classification tag. It exploits localization cues that emerge from training a modified zoom-out architecture tailored for classification tasks, to drive a weakly supervised process that automatically labels a sparse, diverse training set of points likely to belong to classes of interest. Finally, we introduce data-driven regularization functions for the supervised training of CNNs. Our innovation takes the form of a regularizer derived by learning an autoencoder over the set of annotations. This approach leverages an improved representation of label space to inform extraction of features from images

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11820](http://arxiv.org/abs/1908.11820)

##### PDF
[http://arxiv.org/pdf/1908.11820](http://arxiv.org/pdf/1908.11820)

