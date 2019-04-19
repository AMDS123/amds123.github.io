---
layout: post
title: "Generating Training Data for Denoising Real RGB Images via Camera Pipeline Simulation"
date: 2019-04-18 15:04:48
categories: arXiv_CV
tags: arXiv_CV
author: Ronnachai Jaroensri, Camille Biscarrat, Miika Aittala, Fr&#xe9;do Durand
mathjax: true
---

* content
{:toc}

##### Abstract
Image reconstruction techniques such as denoising often need to be applied to the RGB output of cameras and cellphones. Unfortunately, the commonly used additive white noise (AWGN) models do not accurately reproduce the noise and the degradation encountered on these inputs. This is particularly important for learning-based techniques, because the mismatch between training and real world data will hurt their generalization. This paper aims to accurately simulate the degradation and noise transformation performed by camera pipelines. This allows us to generate realistic degradation in RGB images that can be used to train machine learning models. We use our simulation to study the importance of noise modeling for learning-based denoising. Our study shows that a realistic noise model is required for learning to denoise real JPEG images. A neural network trained on realistic noise outperforms the one trained with AWGN by 3 dB. An ablation study of our pipeline shows that simulating denoising and demosaicking is important to this improvement and that realistic demosaicking algorithms, which have been rarely considered, is needed. We believe this simulation will also be useful for other image reconstruction tasks, and we will distribute our code publicly.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08825](http://arxiv.org/abs/1904.08825)

##### PDF
[http://arxiv.org/pdf/1904.08825](http://arxiv.org/pdf/1904.08825)

