---
layout: post
title: "UltraCompression: Framework for High Density Compression of Ultrasound Volumes using Physics Modeling Deep Neural Networks"
date: 2019-01-17 16:42:34
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Debarghya China, Francis Tom, Sumanth Nandamuri, Aupendu Kar, Mukundhan Srinivasan, Pabitra Mitra, Debdoot Sheet
mathjax: true
---

* content
{:toc}

##### Abstract
Ultrasound image compression by preserving speckle-based key information is a challenging task. In this paper, we introduce an ultrasound image compression framework with the ability to retain realism of speckle appearance despite achieving very high-density compression factors. The compressor employs a tissue segmentation method, transmitting segments along with transducer frequency, number of samples and image size as essential information required for decompression. The decompressor is based on a convolutional network trained to generate patho-realistic ultrasound images which convey essential information pertinent to tissue pathology visible in the images. We demonstrate generalizability of the building blocks using two variants to build the compressor. We have evaluated the quality of decompressed images using distortion losses as well as perception loss and compared it with other off the shelf solutions. The proposed method achieves a compression ratio of $725:1$ while preserving the statistical distribution of speckles. This enables image segmentation on decompressed images to achieve dice score of $0.89 \pm 0.11$, which evidently is not so accurately achievable when images are compressed with current standards like JPEG, JPEG 2000, WebP and BPG. We envision this frame work to serve as a roadmap for speckle image compression standards.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.05880](https://arxiv.org/abs/1901.05880)

##### PDF
[https://arxiv.org/pdf/1901.05880](https://arxiv.org/pdf/1901.05880)

