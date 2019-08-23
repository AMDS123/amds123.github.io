---
layout: post
title: "Improved MR to CT synthesis for PET/MR attenuation correction using Imitation Learning"
date: 2019-08-21 12:47:29
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Quantitative
author: Kerstin Kläser, Thomas Varsavsky, Pawel Markiewicz, David Atkinson, Kris Thielemans, Brian Hutton, M Jorge Cardoso, Sebastien Ourselin
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to synthesise Computed Tomography images - commonly known as pseudo CT, or pCT - from MRI input data is commonly assessed using an intensity-wise similarity, such as an L2-norm between the ground truth CT and the pCT. However, given that the ultimate purpose is often to use the pCT as an attenuation map ($\mu$-map) in Positron Emission Tomography Magnetic Resonance Imaging (PET/MRI), minimising the error between pCT and CT is not necessarily optimal. The main objective should be to predict a pCT that, when used as $\mu$-map, reconstructs a pseudo PET (pPET) which is as close as possible to the gold standard PET. To this end, we propose a novel multi-hypothesis deep learning framework that generates pCTs by minimising a combination of the pixel-wise error between pCT and CT and a proposed metric-loss that itself is represented by a convolutional neural network (CNN) and aims to minimise subsequent PET residuals. The model is trained on a database of 400 paired MR/CT/PET image slices. Quantitative results show that the network generates pCTs that seem less accurate when evaluating the Mean Absolute Error on the pCT (69.68HU) compared to a baseline CNN (66.25HU), but lead to significant improvement in the PET reconstruction - 115a.u. compared to baseline 140a.u.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08431](https://arxiv.org/abs/1908.08431)

##### PDF
[https://arxiv.org/pdf/1908.08431](https://arxiv.org/pdf/1908.08431)

