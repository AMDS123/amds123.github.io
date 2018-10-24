---
layout: post
title: "Breast Tumor Segmentation and Shape Classification in Mammograms using Generative Adversarial and Convolutional Neural Network"
date: 2018-10-23 17:08:49
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Classification Detection
author: Vivek Kumar Singh, Hatem A. Rashwan, Santiago Romani, Farhan Akram, Nidhi Pandey, Md. Mostafa Kamal Sarker, Adel Saleh, Meritexell Arenas, Miguel Arquez, Domenec Puig, Jordina Torrents-Barrena
mathjax: true
---

* content
{:toc}

##### Abstract
Mammogram inspection in search of breast tumors is a tough assignment that radiologists must carry out frequently. Therefore, image analysis methods are needed for the detection and delineation of breast masses, which portray crucial morphological information that will support reliable diagnosis. In this paper, we proposed a conditional Generative Adversarial Network (cGAN) devised to segment a breast mass within a region of interest (ROI) in a mammogram. The generative network learns to recognize the breast mass area and to create the binary mask that outlines the breast mass. In turn, the adversarial network learns to distinguish between real (ground truth) and synthetic segmentations, thus enforcing the generative network to create binary masks as realistic as possible. The cGAN works well even when the number of training samples are limited. Therefore, the proposed method outperforms several state-of-the-art approaches. This hypothesis is corroborated by diverse experiments performed on two datasets, the public INbreast and a private in-house dataset. The proposed segmentation model provides a high Dice coefficient and Intersection over Union (IoU) of 94% and 87%, respectively. In addition, a shape descriptor based on a Convolutional Neural Network (CNN) is proposed to classify the generated masks into four mass shapes: irregular, lobular, oval and round. The proposed shape descriptor was trained on Digital Database for Screening Mammography (DDSM) yielding an overall accuracy of 80%, which outperforms the current state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.01687](http://arxiv.org/abs/1809.01687)

##### PDF
[http://arxiv.org/pdf/1809.01687](http://arxiv.org/pdf/1809.01687)

