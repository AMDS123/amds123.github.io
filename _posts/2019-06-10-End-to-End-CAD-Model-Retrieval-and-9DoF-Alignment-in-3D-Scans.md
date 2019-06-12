---
layout: post
title: "End-to-End CAD Model Retrieval and 9DoF Alignment in 3D Scans"
date: 2019-06-10 18:01:42
categories: arXiv_CV
tags: arXiv_CV OCR CNN Prediction
author: Armen Avetisyan, Angela Dai, Matthias Nie&#xdf;ner
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel, end-to-end approach to align CAD models to an 3D scan of a scene, enabling transformation of a noisy, incomplete 3D scan to a compact, CAD reconstruction with clean, complete object geometry. Our main contribution lies in formulating a differentiable Procrustes alignment that is paired with a symmetry-aware dense object correspondence prediction. To simultaneously align CAD models to all the objects of a scanned scene, our approach detects object locations, then predicts symmetry-aware dense object correspondences between scan and CAD geometry in a unified object space, as well as a nearest neighbor CAD model, both of which are then used to inform a differentiable Procrustes alignment. Our approach operates in a fully-convolutional fashion, enabling alignment of CAD models to the objects of a scan in a single forward pass. This enables our method to outperform state-of-the-art approaches by $19.04\%$ for CAD model alignment to scans, with $\approx 250\times$ faster runtime than previous data-driven approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04201](http://arxiv.org/abs/1906.04201)

##### PDF
[http://arxiv.org/pdf/1906.04201](http://arxiv.org/pdf/1906.04201)

