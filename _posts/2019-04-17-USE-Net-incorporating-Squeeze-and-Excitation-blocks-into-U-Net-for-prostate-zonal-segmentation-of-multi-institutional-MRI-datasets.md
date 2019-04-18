---
layout: post
title: "USE-Net: incorporating Squeeze-and-Excitation blocks into U-Net for prostate zonal segmentation of multi-institutional MRI datasets"
date: 2019-04-17 13:02:30
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Leonardo Rundo, Changhee Han, Yudai Nagano, Jin Zhang, Ryuichiro Hataya, Carmelo Militello, Andrea Tangherloni, Marco S. Nobile, Claudio Ferretti, Daniela Besozzi, Maria Carla Gilardi, Salvatore Vitabile, Giancarlo Mauri, Hideki Nakayama, Paolo Cazzaniga
mathjax: true
---

* content
{:toc}

##### Abstract
Prostate cancer is the most common malignant tumors in men but prostate Magnetic Resonance Imaging (MRI) analysis remains challenging. Besides whole prostate gland segmentation, the capability to differentiate between the blurry boundary of the Central Gland (CG) and Peripheral Zone (PZ) can lead to differential diagnosis, since tumor's frequency and severity differ in these regions. To tackle the prostate zonal segmentation task, we propose a novel Convolutional Neural Network (CNN), called USE-Net, which incorporates Squeeze-and-Excitation (SE) blocks into U-Net. Especially, the SE blocks are added after every Encoder (Enc USE-Net) or Encoder-Decoder block (Enc-Dec USE-Net). This study evaluates the generalization ability of CNN-based architectures on three T2-weighted MRI datasets, each one consisting of a different number of patients and heterogeneous image characteristics, collected by different institutions. The following mixed scheme is used for training/testing: (i) training on either each individual dataset or multiple prostate MRI datasets and (ii) testing on all three datasets with all possible training/testing combinations. USE-Net is compared against three state-of-the-art CNN-based architectures (i.e., U-Net, pix2pix, and Mixed-Scale Dense Network), along with a semi-automatic continuous max-flow model. The results show that training on the union of the datasets generally outperforms training on each dataset separately, allowing for both intra-/cross-dataset generalization. Enc USE-Net shows good overall generalization under any training condition, while Enc-Dec USE-Net remarkably outperforms the other methods when trained on all datasets. These findings reveal that the SE blocks' adaptive feature recalibration provides excellent cross-dataset generalization when testing is performed on samples of the datasets used during training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08254](http://arxiv.org/abs/1904.08254)

##### PDF
[http://arxiv.org/pdf/1904.08254](http://arxiv.org/pdf/1904.08254)

