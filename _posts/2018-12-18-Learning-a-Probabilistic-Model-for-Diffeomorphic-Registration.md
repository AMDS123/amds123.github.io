---
layout: post
title: "Learning a Probabilistic Model for Diffeomorphic Registration"
date: 2018-12-18 16:22:41
categories: arXiv_CV
tags: arXiv_CV Regularization Inference Classification
author: Julian Krebs, Herv&#xe9; Delingette, Boris Mailh&#xe9;, Nicholas Ayache, Tommaso Mansi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to learn a low-dimensional probabilistic deformation model from data which can be used for registration and the analysis of deformations. The latent variable model maps similar deformations close to each other in an encoding space. It enables to compare deformations, generate normal or pathological deformations for any new image or to transport deformations from one image pair to any other image. Our unsupervised method is based on variational inference. In particular, we use a conditional variational autoencoder (CVAE) network and constrain transformations to be symmetric and diffeomorphic by applying a differentiable exponentiation layer with a symmetric loss function. We also present a formulation that includes spatial regularization such as diffusion-based filters. Additionally, our framework provides multi-scale velocity field estimations. We evaluated our method on 3-D intra-subject registration using 334 cardiac cine-MRIs. On this dataset, our method showed state-of-the-art performance with a mean DICE score of 81.2% and a mean Hausdorff distance of 7.3mm using 32 latent dimensions compared to three state-of-the-art methods while also demonstrating more regular deformation fields. The average time per registration was 0.32s. Besides, we visualized the learned latent space and show that the encoded deformations can be used to transport deformations and to cluster diseases with a classification accuracy of 83% after applying a linear projection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07460](http://arxiv.org/abs/1812.07460)

##### PDF
[http://arxiv.org/pdf/1812.07460](http://arxiv.org/pdf/1812.07460)

