---
layout: post
title: "Fast Solar Image Classification Using Deep Learning and its Importance for Automation in Solar Physics"
date: 2019-05-31 12:27:55
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Transfer_Learning Classification Deep_Learning Detection
author: John A. Armstrong, Lyndsay Fletcher
mathjax: true
---

* content
{:toc}

##### Abstract
The volume of data being collected in solar physics has exponentially increased over the past decade and with the introduction of the $\textit{Daniel K. Inouye Solar Telescope}$ (DKIST) we will be entering the age of petabyte solar data. Automated feature detection will be an invaluable tool for post-processing of solar images to create catalogues of data ready for researchers to use. We propose a deep learning model to accomplish this; a deep convolutional neural network is adept at feature extraction and processing images quickly. We train our network using data from $\textit{Hinode/Solar Optical Telescope}$ (SOT) H$\alpha$ images of a small subset of solar features with different geometries: filaments, prominences, flare ribbons, sunspots and the quiet Sun ($\textit{i.e.}$ the absence of any of the other four features). We achieve near perfect performance on classifying unseen images from SOT ($\approx$99.9\%) in 4.66 seconds. We also for the first time explore transfer learning in a solar context. Transfer learning uses pre-trained deep neural networks to help train new deep learning models $\textit{i.e.}$ it teaches a new model. We show that our network is robust to changes in resolution by degrading images from SOT resolution ($\approx$0.33$^{\prime \prime}$ at $\lambda$=6563\AA{}) to $\textit{Solar Dynamics Observatory/Atmospheric Imaging Assembly}$ (SDO/AIA) resolution ($\approx$1.2$^{\prime \prime}$) without a change in performance of our network. However, we also observe where the network fails to generalise to sunspots from SDO/AIA bands 1600/1700\AA{} due to small-scale brightenings around the sunspots and prominences in SDO/AIA 304\AA{} due to coronal emission.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13575](http://arxiv.org/abs/1905.13575)

##### PDF
[http://arxiv.org/pdf/1905.13575](http://arxiv.org/pdf/1905.13575)

