---
layout: post
title: "Learning Part Generation and Assembly for Structure-aware Shape Synthesis"
date: 2019-06-16 14:14:33
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Relation
author: Jun Li, Chengjie Niu, Kai Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Learning deep generative models for 3D shape synthesis is largely limited by the difficulty of generating plausible shapes with correct topology and reasonable geometry. Indeed, learning the distribution of plausible 3D shapes seems a daunting task for most existing, structure-oblivious shape representation, given the significant topological variations of 3D objects even within the same shape category. Based on the consensus from 3D shape analysis that shape structure is defined as part composition and mutual relations between parts, we propose to model 3D shape variations with a deep generative network being both Part-Aware and Relation-Aware, named PARANet. The network is composed of an array of per-part VAE-GANs, generating semantic parts composing a complete shape, followed by a part assembly module that estimates a transformation for each part to correlate and assemble them into a plausible structure. Through splitting the generation of part composition and part relations into separate networks, the difficulty of modeling structural variations of 3D shapes is greatly reduced. We demonstrate through extensive experiments that PARANet generates 3D shapes with plausible, diverse and detailed structure, and show two prototype applications: semantic shape segmentation and shape set evolution.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06693](http://arxiv.org/abs/1906.06693)

##### PDF
[http://arxiv.org/pdf/1906.06693](http://arxiv.org/pdf/1906.06693)

