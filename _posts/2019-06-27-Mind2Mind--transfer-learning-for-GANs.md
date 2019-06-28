---
layout: post
title: "Mind2Mind : transfer learning for GANs"
date: 2019-06-27 13:19:29
categories: arXiv_CV
tags: arXiv_CV GAN Transfer_Learning Classification
author: Ya&#xeb;l Fr&#xe9;gier, Jean-Baptiste Gouray
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approach for transfer learning with GAN architectures. In general, transfer learning enables deep networks for classification tasks to be trained with limited computing and data resources. However a similar approach is missing in the specific context of generative tasks. This is partly due to the fact that the extremal layers of the two networks of a GAN, which should be learned during transfer, are on two opposite sides. This requires back-propagating information through both networks, which is computationally expensive. We develop a method to directly train these extremal layers against each other, by-passing all the intermediate layers. We also prove rigorously, for Wasserstein GANs, a theorem ensuring the convergence of the learning of the transferred GAN. Finally, we compare our method to state-of-the-art methods and show that our method converges much faster and requires less data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11613](http://arxiv.org/abs/1906.11613)

##### PDF
[http://arxiv.org/pdf/1906.11613](http://arxiv.org/pdf/1906.11613)

