---
layout: post
title: "Diagnostic Accuracy of Content Based Dermatoscopic Image Retrieval with Deep Classification Features"
date: 2018-10-22 18:20:01
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN Classification Prediction
author: Philipp Tschandl, Giuseppe Argenziano, Majid Razmara, Jordan Yap
mathjax: true
---

* content
{:toc}

##### Abstract
Background: Automated classification of medical images through neural networks can reach high accuracy rates but lack interpretability. 
 Objectives: To compare the diagnostic accuracy obtained by using content based image retrieval (CBIR) to retrieve visually similar dermatoscopic images with corresponding disease labels against predictions made by a neural network. 
 Methods: A neural network was trained to predict disease classes on dermatoscopic images from three retrospectively collected image datasets containing 888, 2750 and 16691 images respectively. Diagnosis predictions were made based on the most commonly occurring diagnosis in visually similar images, or based on the top-1 class prediction of the softmax output from the network. Outcome measures were area under the ROC curve for predicting a malignant lesion (AUC), multiclass-accuracy and mean average precision (mAP), measured on unseen test images of the corresponding dataset. 
 Results: In all three datasets the skin cancer predictions from CBIR (evaluating the 16 most similar images) showed AUC values similar to softmax predictions (0.842, 0.806 and 0.852 versus 0.830, 0.810 and 0.847 respectively; p-value&gt;0.99 for all). Similarly, the multiclass-accuracy of CBIR was comparable to softmax predictions. Networks trained for detecting only 3 classes performed better on a dataset with 8 classes when using CBIR as compared to softmax predictions (mAP 0.184 vs. 0.368 and 0.198 vs. 0.403 respectively). 
 Conclusions: Presenting visually similar images based on features from a neural network shows comparable accuracy to the softmax probability-based diagnoses of convolutional neural networks. CBIR may be more helpful than a softmax classifier in improving diagnostic accuracy of clinicians in a routine clinical setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09487](http://arxiv.org/abs/1810.09487)

##### PDF
[http://arxiv.org/pdf/1810.09487](http://arxiv.org/pdf/1810.09487)

