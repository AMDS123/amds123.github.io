---
layout: post
title: "Fast Dynamic Perfusion and Angiography Reconstruction using an end-to-end 3D Convolutional Neural Network"
date: 2019-08-24 15:51:20
categories: arXiv_CV
tags: arXiv_CV CNN
author: Sahar Yousefi, Lydiane Hirschler, Merlijn van der Plas, Mohamed S. Elmahdy, Hessam Sokooti, Matthias Van Osch, Marius Staring
mathjax: true
---

* content
{:toc}

##### Abstract
Hadamard time-encoded pseudo-continuous arterial spin labeling (te-pCASL) is a signal-to-noise ratio (SNR)-efficient MRI technique for acquiring dynamic pCASL signals that encodes the temporal information into the labeling according to a Hadamard matrix. In the decoding step, the contribution of each sub-bolus can be isolated resulting in dynamic perfusion scans. When acquiring te-ASL both with and without flow-crushing, the ASL-signal in the arteries can be isolated resulting in 4D-angiographic information. However, obtaining multi-timepoint perfusion and angiographic data requires two acquisitions. In this study, we propose a 3D Dense-Unet convolutional neural network with a multi-level loss function for reconstructing multi-timepoint perfusion and angiographic information from an interleaved 50%-sampled crushed and 50%-sampled non-crushed data, thereby negating the additional scan time. We present a framework to generate dynamic pCASL training and validation data, based on models of the intravascular and extravascular te-pCASL signals. The proposed network achieved SSIM values of 92.89 $\pm$ 1.18 and 96.50 $\pm$ 0.70 respectively for 4D perfusion and angiographic data reconstruction for 313 test data-sets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08947](http://arxiv.org/abs/1908.08947)

##### PDF
[http://arxiv.org/pdf/1908.08947](http://arxiv.org/pdf/1908.08947)

