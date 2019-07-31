---
layout: post
title: "Synthesis and Inpainting-Based MR-CT Registration for Image-Guided Thermal Ablation of Liver Tumors"
date: 2019-07-30 15:37:16
categories: arXiv_CV
tags: arXiv_CV GAN
author: Dongming Wei, Sahar Ahmad, Jiayu Huo, Wen Peng, Yunhao Ge, Zhong Xue, Pew-Thian Yap, Wentao Li, Dinggang Shen, Qian Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Thermal ablation is a minimally invasive procedure for treat-ing small or unresectable tumors. Although CT is widely used for guiding ablation procedures, the contrast of tumors against surrounding normal tissues in CT images is often poor, aggravating the difficulty in accurate thermal ablation. In this paper, we propose a fast MR-CT image registration method to overlay a pre-procedural MR (pMR) image onto an intra-procedural CT (iCT) image for guiding the thermal ablation of liver tumors. By first using a Cycle-GAN model with mutual information constraint to generate synthesized CT (sCT) image from the cor-responding pMR, pre-procedural MR-CT image registration is carried out through traditional mono-modality CT-CT image registration. At the intra-procedural stage, a partial-convolution-based network is first used to inpaint the probe and its artifacts in the iCT image. Then, an unsupervised registration network is used to efficiently align the pre-procedural CT (pCT) with the inpainted iCT (inpCT) image. The final transformation from pMR to iCT is obtained by combining the two estimated transformations,i.e., (1) from the pMR image space to the pCT image space (through sCT) and (2) from the pCT image space to the iCT image space (through inpCT). Experimental results confirm that the proposed method achieves high registration accuracy with a very fast computational speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13020](http://arxiv.org/abs/1907.13020)

##### PDF
[http://arxiv.org/pdf/1907.13020](http://arxiv.org/pdf/1907.13020)

