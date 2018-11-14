---
layout: post
title: "GANomaly: Semi-Supervised Anomaly Detection via Adversarial Training"
date: 2018-11-13 15:56:32
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference Detection
author: Samet Akcay, Amir Atapour-Abarghouei, Toby P. Breckon
mathjax: true
---

* content
{:toc}

##### Abstract
Anomaly detection is a classical problem in computer vision, namely the determination of the normal from the abnormal when datasets are highly biased towards one class (normal) due to the insufficient sample size of the other class (abnormal). While this can be addressed as a supervised learning problem, a significantly more challenging problem is that of detecting the unknown/unseen anomaly case that takes us instead into the space of a one-class, semi-supervised learning paradigm. We introduce such a novel anomaly detection model, by using a conditional generative adversarial network that jointly learns the generation of high-dimensional image space and the inference of latent space. Employing encoder-decoder-encoder sub-networks in the generator network enables the model to map the input image to a lower dimension vector, which is then used to reconstruct the generated output image. The use of the additional encoder network maps this generated image to its latent representation. Minimizing the distance between these images and the latent vectors during training aids in learning the data distribution for the normal samples. As a result, a larger distance metric from this learned data distribution at inference time is indicative of an outlier from that distribution - an anomaly. Experimentation over several benchmark datasets, from varying domains, shows the model efficacy and superiority over previous state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.06725](http://arxiv.org/abs/1805.06725)

##### PDF
[http://arxiv.org/pdf/1805.06725](http://arxiv.org/pdf/1805.06725)

