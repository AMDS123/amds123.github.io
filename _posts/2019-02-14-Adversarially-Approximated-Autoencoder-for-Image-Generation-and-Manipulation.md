---
layout: post
title: "Adversarially Approximated Autoencoder for Image Generation and Manipulation"
date: 2019-02-14 19:54:13
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Inference
author: Wenju Xu, Shawn Keshmiri, Guanghui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Regularized autoencoders learn the latent codes, a structure with the regularization under the distribution, which enables them the capability to infer the latent codes given observations and generate new samples given the codes. However, they are sometimes ambiguous as they tend to produce reconstructions that are not necessarily faithful reproduction of the inputs. The main reason is to enforce the learned latent code distribution to match a prior distribution while the true distribution remains unknown. To improve the reconstruction quality and learn the latent space a manifold structure, this work present a novel approach using the adversarially approximated autoencoder (AAAE) to investigate the latent codes with adversarial approximation. Instead of regularizing the latent codes by penalizing on the distance between the distributions of the model and the target, AAAE learns the autoencoder flexibly and approximates the latent space with a simpler generator. The ratio is estimated using generative adversarial network (GAN) to enforce the similarity of the distributions. Additionally, the image space is regularized with an additional adversarial regularizer. The proposed approach unifies two deep generative models for both latent space inference and diverse generation. The learning scheme is realized without regularization on the latent codes, which also encourages faithful reconstruction. Extensive validation experiments on four real-world datasets demonstrate the superior performance of AAAE. In comparison to the state-of-the-art approaches, AAAE generates samples with better quality and shares the properties of regularized autoencoder with a nice latent manifold structure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05581](http://arxiv.org/abs/1902.05581)

##### PDF
[http://arxiv.org/pdf/1902.05581](http://arxiv.org/pdf/1902.05581)

