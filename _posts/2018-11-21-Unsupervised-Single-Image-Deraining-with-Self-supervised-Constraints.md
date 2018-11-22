---
layout: post
title: "Unsupervised Single Image Deraining with Self-supervised Constraints"
date: 2018-11-21 02:50:06
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Xin Jin, Zhibo Chen, Jianxin Lin, Zhikai Chen, Wei Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing single image deraining methods require learning supervised models from a large set of paired synthetic training data, which limits their generality, scalability and practicality in real-world multimedia applications. Besides, due to lack of labeled-supervised constraints, directly applying existing unsupervised frameworks to the image deraining task will suffer from low-quality recovery. Therefore, we propose an Unsupervised Deraining Generative Adversarial Network (UD-GAN) to tackle above problems by introducing self-supervised constraints from the intrinsic statistics of unpaired rainy and clean images. Specifically, we firstly design two collaboratively optimized modules, namely Rain Guidance Module (RGM) and Background Guidance Module (BGM), to take full advantage of rainy image characteristics: The RGM is designed to discriminate real rainy images from fake rainy images which are created based on outputs of the generator with BGM. Simultaneously, the BGM exploits a hierarchical Gaussian-Blur gradient error to ensure background consistency between rainy input and de-rained output. Secondly, a novel luminance-adjusting adversarial loss is integrated into the clean image discriminator considering the built-in luminance difference between real clean images and derained images. Comprehensive experiment results on various benchmarking datasets and different training settings show that UD-GAN outperforms existing image deraining methods in both quantitative and qualitative comparisons.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08575](http://arxiv.org/abs/1811.08575)

##### PDF
[http://arxiv.org/pdf/1811.08575](http://arxiv.org/pdf/1811.08575)

