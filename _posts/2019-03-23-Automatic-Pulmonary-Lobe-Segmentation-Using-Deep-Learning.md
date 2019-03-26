---
layout: post
title: "Automatic Pulmonary Lobe Segmentation Using Deep Learning"
date: 2019-03-23 20:31:45
categories: arXiv_AI
tags: arXiv_AI Segmentation CNN Deep_Learning Detection
author: Hao Tang, Chupeng Zhang, Xiaohui Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Pulmonary lobe segmentation is an important task for pulmonary disease related Computer Aided Diagnosis systems (CADs). Classical methods for lobe segmentation rely on successful detection of fissures and other anatomical information such as the location of blood vessels and airways. With the success of deep learning in recent years, Deep Convolutional Neural Network (DCNN) has been widely applied to analyze medical images like Computed Tomography (CT) and Magnetic Resonance Imaging (MRI), which, however, requires a large number of ground truth annotations. In this work, we release our manually labeled 50 CT scans which are randomly chosen from the LUNA16 dataset and explore the use of deep learning on this task. We propose pre-processing CT image by cropping region that is covered by the convex hull of the lungs in order to mitigate the influence of noise from outside the lungs. Moreover, we design a hybrid loss function with dice loss to tackle extreme class imbalance issue and focal loss to force model to focus on voxels that are hard to be discriminated. To validate the robustness and performance of our proposed framework trained with a small number of training examples, we further tested our model on CT scans from an independent dataset. Experimental results show the robustness of the proposed approach, which consistently improves performance across different datasets by a maximum of $5.87\%$ as compared to a baseline model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09879](http://arxiv.org/abs/1903.09879)

##### PDF
[http://arxiv.org/pdf/1903.09879](http://arxiv.org/pdf/1903.09879)

