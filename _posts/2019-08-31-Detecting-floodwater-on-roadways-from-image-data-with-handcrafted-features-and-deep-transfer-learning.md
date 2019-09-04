---
layout: post
title: "Detecting floodwater on roadways from image data with handcrafted features and deep transfer learning"
date: 2019-08-31 04:35:56
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Transfer_Learning Classification
author: Cem Sazara, Mecit Cetin, Khan M. Iftekharuddin
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting roadway segments inundated due to floodwater has important applications for vehicle routing and traffic management decisions. This paper proposes a set of algorithms to automatically detect floodwater that may be present in an image captured by mobile phones or other types of optical cameras. For this purpose, image classification and flood area segmentation methods are developed. For the classification task, we used Local Binary Patterns (LBP), Histogram of Oriented Gradients (HOG) and pre-trained deep neural network (VGG-16) as feature extractors and trained logistic regression, k-nearest neighbors, and decision tree classifiers on the extracted features. Pre-trained VGG-16 network with logistic regression classifier outperformed all other methods. For the flood area segmentation task, we investigated superpixel based methods and Fully Convolutional Neural Network (FCN). Similar to the classification task, we trained logistic regression and k-nearest neighbors classifiers on the superpixel areas and compared that with an end-to-end trained FCN. Conditional Random Fields (CRF) method was applied after both segmentation methods to post-process coarse segmentation results. FCN offered the highest scores in all metrics; it was followed by superpixel-based logistic regression and then superpixel-based KNN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00125](http://arxiv.org/abs/1909.00125)

##### PDF
[http://arxiv.org/pdf/1909.00125](http://arxiv.org/pdf/1909.00125)

