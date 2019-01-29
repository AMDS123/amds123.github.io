---
layout: post
title: "Virtual Conditional Generative Adversarial Networks"
date: 2019-01-25 07:15:17
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Haifeng Shi, Guanyu Cai, Yuqin Wang, Shaohua Shang, Lianghua He
mathjax: true
---

* content
{:toc}

##### Abstract
When trained on multimodal image datasets, normal Generative Adversarial Networks (GANs) are usually outperformed by class-conditional GANs and ensemble GANs, but conditional GANs is restricted to labeled datasets and ensemble GANs lack efficiency. We propose a novel GAN variant called virtual conditional GAN (vcGAN) which is not only an ensemble GAN with multiple generative paths while adding almost zero network parameters, but also a conditional GAN that can be trained on unlabeled datasets without explicit clustering steps or objectives other than the adversary loss. Inside the vcGAN's generator, a learnable ``analog-to-digital converter (ADC)" module maps a slice of the inputted multivariate Gaussian noise to discrete/digital noise (virtual label), according to which a selector selects the corresponding generative path to produce the sample. All the generative paths share the same decoder network while in each path the decoder network is fed with a concatenation of a different pre-computed amplified one-hot vector and the inputted Gaussian noise. We conducted a lot of experiments on several balanced/imbalanced image datasets to demonstrate that vcGAN converges faster and achieves improved Frech\'et Inception Distance (FID). In addition, we show the training byproduct that the ADC in vcGAN learned the categorical probability of each mode and that each generative path generates samples of specific mode, which enables class-conditional sampling. Codes are available at \url{https://github.com/annonnymmouss/vcgan}

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09822](http://arxiv.org/abs/1901.09822)

##### PDF
[http://arxiv.org/pdf/1901.09822](http://arxiv.org/pdf/1901.09822)

