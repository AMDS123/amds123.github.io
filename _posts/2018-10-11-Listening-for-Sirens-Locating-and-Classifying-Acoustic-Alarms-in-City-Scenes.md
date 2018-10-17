---
layout: post
title: "Listening for Sirens: Locating and Classifying Acoustic Alarms in City Scenes"
date: 2018-10-11 12:56:56
categories: arXiv_AI
tags: arXiv_AI Segmentation Semantic_Segmentation Classification Detection
author: Letizia Marchegiani, Paul Newman
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is about alerting acoustic event detection and sound source localisation in an urban scenario. Specifically, we are interested in spotting the presence of horns, and sirens of emergency vehicles. In order to obtain a reliable system able to operate robustly despite the presence of traffic noise, which can be copious, unstructured and unpredictable, we propose to treat the spectrograms of incoming stereo signals as images, and apply semantic segmentation, based on a Unet architecture, to extract the target sound from the background noise. In a multi-task learning scheme, together with signal denoising, we perform acoustic event classification to identify the nature of the alerting sound. Lastly, we use the denoised signals to localise the acoustic source on the horizon plane, by regressing the direction of arrival of the sound through a CNN architecture. Our experimental evaluation shows an average classification rate of 94%, and a median absolute error on the localisation of 7.5{\deg} when operating on audio frames of 0.5s, and of 2.5{\deg} when operating on frames of 2.5s. The system offers excellent performance in particularly challenging scenarios, where the noise level is remarkably high.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04989](https://arxiv.org/abs/1810.04989)

##### PDF
[https://arxiv.org/pdf/1810.04989](https://arxiv.org/pdf/1810.04989)

