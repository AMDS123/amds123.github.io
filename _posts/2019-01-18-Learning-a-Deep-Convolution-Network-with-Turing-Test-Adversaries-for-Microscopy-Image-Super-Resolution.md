---
layout: post
title: "Learning a Deep Convolution Network with Turing Test Adversaries for Microscopy Image Super Resolution"
date: 2019-01-18 19:55:19
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution CNN VQA
author: Francis Tom, Himanshu Sharma, Dheeraj Mundhra, Tathagato Rai Dastidar, Debdoot Sheet
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarially trained deep neural networks have significantly improved performance of single image super resolution, by hallucinating photorealistic local textures, thereby greatly reducing the perception difference between a real high resolution image and its super resolved (SR) counterpart. However, application to medical imaging requires preservation of diagnostically relevant features while refraining from introducing any diagnostically confusing artifacts. We propose using a deep convolutional super resolution network (SRNet) trained for (i) minimising reconstruction loss between the real and SR images, and (ii) maximally confusing learned relativistic visual Turing test (rVTT) networks to discriminate between (a) pair of real and SR images (T1) and (b) pair of patches in real and SR selected from region of interest (T2). The adversarial loss of T1 and T2 while backpropagated through SRNet helps it learn to reconstruct pathorealism in the regions of interest such as white blood cells (WBC) in peripheral blood smears or epithelial cells in histopathology of cancerous biopsy tissues, which are experimentally demonstrated here. Experiments performed for measuring signal distortion loss using peak signal to noise ratio (pSNR) and structural similarity (SSIM) with variation of SR scale factors, impact of rVTT adversarial losses, and impact on reporting using SR on a commercially available artificial intelligence (AI) digital pathology system substantiate our claims.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06405](http://arxiv.org/abs/1901.06405)

##### PDF
[http://arxiv.org/pdf/1901.06405](http://arxiv.org/pdf/1901.06405)

