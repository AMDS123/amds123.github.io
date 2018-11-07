---
layout: post
title: "Convolutional LSTMs for Cloud-Robust Segmentation of Remote Sensing Imagery"
date: 2018-10-28 17:58:22
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN RNN Classification
author: Marc Rußwurm, Marco Körner
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic spatiotemporal processes on the Earth can be observed by an increasing number of optical Earth observation satellites that measure spectral reflectance at multiple spectral bands in regular intervals. Clouds partially covering the surface is an omnipresent challenge for the majority of remote sensing approaches that are not robust regarding cloud coverage. In these approaches, clouds are typically handled by cherry-picking cloud-free observations or by pre-classification of cloudy pixels and subsequent masking. In this work, we demonstrate the robustness of a straightforward convolutional long short-term memory network for vegetation classification using all available cloudy and non-cloudy satellite observations. We visualize the internal gate activations within the recurrent cells and find that, in some cells, modulation and input gates close on cloudy pixels. This indicates that the network has internalized a cloud-filtering mechanism without being specifically trained on cloud labels. The robustness regarding clouds is further demonstrated by experiments on sequences with varying degrees of cloud coverage where our network achieved similar accuracies on all cloudy and non-cloudy datasets. Overall, our results question the necessity of sophisticated pre-processing pipelines if robust classification methods are utilized.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.02471](https://arxiv.org/abs/1811.02471)

##### PDF
[https://arxiv.org/pdf/1811.02471](https://arxiv.org/pdf/1811.02471)

