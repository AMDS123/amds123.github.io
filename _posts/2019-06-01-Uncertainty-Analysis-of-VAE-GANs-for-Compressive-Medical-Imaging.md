---
layout: post
title: "Uncertainty Analysis of VAE-GANs for Compressive Medical Imaging"
date: 2019-06-01 08:13:07
categories: arXiv_CV
tags: arXiv_CV GAN Prediction
author: Vineet Edupuganti, Morteza Mardani, Joseph Cheng, Shreyas Vasanawala, John Pauly
mathjax: true
---

* content
{:toc}

##### Abstract
Reliable medical image recovery is crucial for accurate diagnoses and patient wellbeing. However, high resolution imaging from limited sensory data leaves substantial uncertainty about the authenticity of the recovered pixels. This study aims to quantify this uncertainty so as to guide radiologists about the confidence of their diagnoses. We put forth a probabilistic recovery scheme based on VAE-GANs, comprised of a VAE generator and multi-layer CNN discriminator, that maps out low-quality images with aliasing artifacts to diagnostic-quality ones. We leverage Stein's Unbiased Risk Estimator (SURE) as a proxy for the prediction error, which includes a divergence term (trace of the end-to-end network Jacobian) quantifying the estimation uncertainty. Extensive empirical experiments are performed for the task of magnetic resonance (MR) image recovery using a dataset of pediatric Knee images. We statistically analyze the output distribution of the model using Monte Carlo sampling to gauge the extent of variance, bias, and error across reconstructions. The results indicate that uncertainty level is significantly influenced by the hyperparameter setting and network architecture. The key observations are that the pixel uncertainty level: 1) increases as the GAN loss weight rises; and 2) decreases as we add more recurrent units to the generator network (cascade of VAEs and data consistency layers).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.11228](https://arxiv.org/abs/1901.11228)

##### PDF
[https://arxiv.org/pdf/1901.11228](https://arxiv.org/pdf/1901.11228)

