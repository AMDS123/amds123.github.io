---
layout: post
title: "Deep Predictive Video Compression with Bi-directional Prediction"
date: 2019-04-05 07:43:02
categories: arXiv_CV
tags: arXiv_CV Attention Deep_Learning Prediction
author: Woonsung Park, Munchurl Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep image compression has shown a big progress in terms of coding efficiency and image quality improvement. However, relatively less attention has been put on video compression using deep learning networks. In the paper, we first propose a deep learning based bi-predictive coding network, called BP-DVC Net, for video compression. Learned from the lesson of the conventional video coding, a B-frame coding structure is incorporated in our BP-DVC Net. While the bi-predictive coding in the conventional video codecs requires to transmit to decoder sides the motion vectors for block motion and the residues from prediction, our BP-DVC Net incorporates optical flow estimation networks in both encoder and decoder sides so as not to transmit the motion information to the decoder sides for coding efficiency improvement. Also, a bi-prediction network in the BP-DVC Net is proposed and used to precisely predict the current frame and to yield the resulting residues as small as possible. Furthermore, our BP-DVC Net allows for the compressive feature maps to be entropy-coded using the temporal context among the feature maps of adjacent frames. The BP-DVC Net has an end-to-end video compression architecture with newly designed flow and prediction losses. Experimental results show that the compression performance of our proposed method is comparable to those of H.264, HEVC in terms of PSNR and MS-SSIM.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02909](https://arxiv.org/abs/1904.02909)

##### PDF
[https://arxiv.org/pdf/1904.02909](https://arxiv.org/pdf/1904.02909)

