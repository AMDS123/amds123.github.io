---
layout: post
title: "MetaStyle: Three-Way Trade-Off Among Speed, Flexibility, and Quality in Neural Style Transfer"
date: 2018-12-13 02:25:10
categories: arXiv_AI
tags: arXiv_AI Style_Transfer Optimization Quantitative
author: Chi Zhang, Yixin Zhu, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
An unprecedented booming has been witnessed in the research area of artistic style transfer ever since Gatys et al. introduced the neural method. One of the remaining challenges is to balance a trade-off among three critical aspects---speed, flexibility, and quality: (i) the vanilla optimization-based algorithm produces impressive results for arbitrary styles, but is unsatisfyingly slow due to its iterative nature, (ii) the fast approximation methods based on feed-forward neural networks generate satisfactory artistic effects but bound to only a limited number of styles, and (iii) feature-matching methods like AdaIN achieve arbitrary style transfer in a real-time manner but at a cost of the compromised quality. We find it considerably difficult to balance the trade-off well merely using a single feed-forward step and ask, instead, whether there exists an algorithm that could adapt quickly to any style, while the adapted model maintains high efficiency and good image quality. Motivated by this idea, we propose a novel method, coined MetaStyle, which formulates the neural style transfer as a bilevel optimization problem and combines learning with only a few post-processing update steps to adapt to a fast approximation model with satisfying artistic effects, comparable to the optimization-based methods for an arbitrary style. The qualitative and quantitative analysis in the experiments demonstrates that the proposed approach achieves high-quality arbitrary artistic style transfer effectively, with a good trade-off among speed, flexibility, and quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05233](http://arxiv.org/abs/1812.05233)

##### PDF
[http://arxiv.org/pdf/1812.05233](http://arxiv.org/pdf/1812.05233)

