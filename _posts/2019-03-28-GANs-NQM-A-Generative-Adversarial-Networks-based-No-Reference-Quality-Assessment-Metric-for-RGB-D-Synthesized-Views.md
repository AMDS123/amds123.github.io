---
layout: post
title: "GANs-NQM: A Generative Adversarial Networks based No Reference Quality Assessment Metric for RGB-D Synthesized Views"
date: 2019-03-28 16:11:42
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Suiyi Ling, Jing Li, Junle Wang, Patrick Le Callet
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we proposed a no-reference (NR) quality metric for RGB plus image-depth (RGB-D) synthesis images based on Generative Adversarial Networks (GANs), namely GANs-NQM. Due to the failure of the inpainting on dis-occluded regions in RGB-D synthesis process, to capture the non-uniformly distributed local distortions and to learn their impact on perceptual quality are challenging tasks for objective quality metrics. In our study, based on the characteristics of GANs, we proposed i) a novel training strategy of GANs for RGB-D synthesis images using existing large-scale computer vision datasets rather than RGB-D dataset; ii) a referenceless quality metric based on the trained discriminator by learning a `Bag of Distortion Word' (BDW) codebook and a local distortion regions selector; iii) a hole filling inpainter, i.e., the generator of the trained GANs, for RGB-D dis-occluded regions as a side outcome. According to the experimental results on IRCCyN/IVC DIBR database, the proposed model outperforms the state-of-the-art quality metrics, in addition, is more applicable in real scenarios. The corresponding context inpainter also shows appealing results over other inpainting algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12088](http://arxiv.org/abs/1903.12088)

##### PDF
[http://arxiv.org/pdf/1903.12088](http://arxiv.org/pdf/1903.12088)

