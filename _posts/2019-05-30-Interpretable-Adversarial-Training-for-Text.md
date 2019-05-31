---
layout: post
title: "Interpretable Adversarial Training for Text"
date: 2019-05-30 05:55:58
categories: arXiv_CL
tags: arXiv_CL Regularization Review Adversarial Sparse Embedding Gradient_Descent
author: Samuel Barham, Soheil Feizi
mathjax: true
---

* content
{:toc}

##### Abstract
Generating high-quality and interpretable adversarial examples in the text domain is a much more daunting task than it is in the image domain. This is due partly to the discrete nature of text, partly to the problem of ensuring that the adversarial examples are still probable and interpretable, and partly to the problem of maintaining label invariance under input perturbations. In order to address some of these challenges, we introduce sparse projected gradient descent (SPGD), a new approach to crafting interpretable adversarial examples for text. SPGD imposes a directional regularization constraint on input perturbations by projecting them onto the directions to nearby word embeddings with highest cosine similarities. This constraint ensures that perturbations move each word embedding in an interpretable direction (i.e., towards another nearby word embedding). Moreover, SPGD imposes a sparsity constraint on perturbations at the sentence level by ignoring word-embedding perturbations whose norms are below a certain threshold. This constraint ensures that our method changes only a few words per sequence, leading to higher quality adversarial examples. Our experiments with the IMDB movie review dataset show that the proposed SPGD method improves adversarial example interpretability and likelihood (evaluated by average per-word perplexity) compared to state-of-the-art methods, while suffering little to no loss in training performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12864](http://arxiv.org/abs/1905.12864)

##### PDF
[http://arxiv.org/pdf/1905.12864](http://arxiv.org/pdf/1905.12864)

