---
layout: post
title: "Emphasis Regularisation by Gradient Rescaling for Training Deep Neural Networks with Noisy Labels"
date: 2019-05-27 13:59:08
categories: arXiv_CV
tags: arXiv_CV
author: Xinshao Wang, Yang Hua, Elyor Kodirov, Neil Robertson
mathjax: true
---

* content
{:toc}

##### Abstract
It is fundamental and challenging to train robust and accurate Deep Neural Networks (DNNs) when noisy labels exist. Although great progress has been made, there is still one crucial research question which is not thoroughly explored yet: What training examples should be focused and how much more should they be emphasised when training DNNs under label noise? In this work, we study this question and propose gradient rescaling (GR) to solve it. GR modifies the magnitude of logit vector's gradient to emphasise on relatively easier training data points when severe noise exists, which functions as explicit emphasis regularisation to improve the generalisation performance of DNNs. Apart from regularisation, we also interpret GR from the perspectives of sample reweighting and designing robust loss functions. Therefore, our proposed GR helps connect these three approaches in the literature. We empirically demonstrate that GR is highly noise-robust and outperforms the state-of-the-art noise-tolerant algorithms by a large margin, e.g., increasing 7% on CIFAR-100 with 40% noisy labels. It is also significantly superior to standard regularisors. Furthermore, we present comprehensive ablation studies to explore the behaviours of GR under different cases, which is informative for applying GR in real-world scenarios.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11233](https://arxiv.org/abs/1905.11233)

##### PDF
[https://arxiv.org/pdf/1905.11233](https://arxiv.org/pdf/1905.11233)

