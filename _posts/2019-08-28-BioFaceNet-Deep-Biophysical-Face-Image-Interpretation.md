---
layout: post
title: "BioFaceNet: Deep Biophysical Face Image Interpretation"
date: 2019-08-28 07:28:48
categories: arXiv_CV
tags: arXiv_CV Face CNN Quantitative
author: Sarah Alotaibi, William Smith
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present BioFaceNet, a deep CNN that learns to decompose a single face image into biophysical parameters maps, diffuse and specular shading maps as well as estimating the spectral power distribution of the scene illuminant and the spectral sensitivity of the camera. The network comprises a fully convolutional encoder for estimating the spatial maps with a fully connected branch for estimating the vector quantities. The network is trained using a self-supervised appearance loss computed via a model-based decoder. The task is highly underconstrained so we impose a number of model-based priors. Skin spectral reflectance is restricted to a biophysical model, we impose a statistical prior on camera spectral sensitivities, a physical constraint on illumination spectra, a sparsity prior on specular reflections and direct supervision on diffuse shading using a rough shape proxy. We show convincing qualitative results on in-the-wild data and introduce a benchmark for quantitative evaluation on this new task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10578](http://arxiv.org/abs/1908.10578)

##### PDF
[http://arxiv.org/pdf/1908.10578](http://arxiv.org/pdf/1908.10578)

