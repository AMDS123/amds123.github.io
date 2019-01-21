---
layout: post
title: "Learning Spatial Pyramid Attentive Pooling in Image Synthesis and Image-to-Image Translation"
date: 2019-01-18 16:23:37
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Optimization
author: Wei Sun, Tianfu Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Image synthesis and image-to-image translation are two important generative learning tasks. Remarkable progress has been made by learning Generative Adversarial Networks (GANs)~\cite{goodfellow2014generative} and cycle-consistent GANs (CycleGANs)~\cite{zhu2017unpaired} respectively. This paper presents a method of learning Spatial Pyramid Attentive Pooling (SPAP) which is a novel architectural unit and can be easily integrated into both generators and discriminators in GANs and CycleGANs. The proposed SPAP integrates Atrous spatial pyramid~\cite{chen2018deeplab}, a proposed cascade attention mechanism and residual connections~\cite{he2016deep}. It leverages the advantages of the three components to facilitate effective end-to-end generative learning: (i) the capability of fusing multi-scale information by ASPP; (ii) the capability of capturing relative importance between both spatial locations (especially multi-scale context) or feature channels by attention; (iii) the capability of preserving information and enhancing optimization feasibility by residual connections. Coarse-to-fine and fine-to-coarse SPAP are studied and intriguing attention maps are observed in both tasks. In experiments, the proposed SPAP is tested in GANs on the Celeba-HQ-128 dataset~\cite{karras2017progressive}, and tested in CycleGANs on the Image-to-Image translation datasets including the Cityscape dataset~\cite{cordts2016cityscapes}, Facade and Aerial Maps dataset~\cite{zhu2017unpaired}, both obtaining better performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06322](http://arxiv.org/abs/1901.06322)

##### PDF
[http://arxiv.org/pdf/1901.06322](http://arxiv.org/pdf/1901.06322)

