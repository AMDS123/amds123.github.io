---
layout: post
title: "A Surprisingly Effective Fix for Deep Latent Variable Modeling of Text"
date: 2019-09-02 21:08:00
categories: arXiv_CL
tags: arXiv_CL Represenation_Learning Language_Model
author: Bohan Li, Junxian He, Graham Neubig, Taylor Berg-Kirkpatrick, Yiming Yang
mathjax: true
---

* content
{:toc}

##### Abstract
When trained effectively, the Variational Autoencoder (VAE) is both a powerful language model and an effective representation learning framework. In practice, however, VAEs are trained with the evidence lower bound (ELBO) as a surrogate objective to the intractable marginal data likelihood. This approach to training yields unstable results, frequently leading to a disastrous local optimum known as posterior collapse. In this paper, we investigate a simple fix for posterior collapse which yields surprisingly effective results. The combination of two known heuristics, previously considered only in isolation, substantially improves held-out likelihood, reconstruction, and latent representation learning when compared with previous state-of-the-art methods. More interestingly, while our experiments demonstrate superiority on these principle evaluations, our method obtains a worse ELBO. We use these results to argue that the typical surrogate objective for VAEs may not be sufficient or necessarily appropriate for balancing the goals of representation learning and data distribution modeling.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00868](http://arxiv.org/abs/1909.00868)

##### PDF
[http://arxiv.org/pdf/1909.00868](http://arxiv.org/pdf/1909.00868)

