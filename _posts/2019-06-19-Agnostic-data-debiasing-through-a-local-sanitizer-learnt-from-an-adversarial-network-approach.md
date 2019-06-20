---
layout: post
title: "Agnostic data debiasing through a local sanitizer learnt from an adversarial network approach"
date: 2019-06-19 00:20:58
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Relation
author: Ulrich A&#xef;vodji, Fran&#xe7;ois Bidet, S&#xe9;bastien Gambs, Rosin Claude Ngueveu, Alain Tapp
mathjax: true
---

* content
{:toc}

##### Abstract
The widespread use of automated decision processes in many areas of our society raises serious ethical issues concerning the fairness of the process and the possible resulting discriminations. In this work, we propose a novel approach called \gansan whose objective is to prevent the possibility of \emph{any} discrimination i.e., direct and indirect) based on a sensitive attribute by removing the attribute itself as well as the existing correlations with the remaining attributes. Our sanitization algorithm \gansan is partially inspired by the powerful framework of generative adversarial networks (in particuler the Cycle-GANs), which offers a flexible way to learn a distribution empirically or to translate between two different distributions. 
 In contrast to prior work, one of the strengths of our approach is that the sanitization is performed in the same space as the original data by only modifying the other attributes as little as possible and thus preserving the interpretability of the sanitized data. As a consequence, once the sanitizer is trained, it can be applied to new data, such as for instance, locally by an individual on his profile before releasing it. Finally, experiments on a real dataset demonstrate the effectiveness of the proposed approach as well as the achievable trade-off between fairness and utility.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07858](http://arxiv.org/abs/1906.07858)

##### PDF
[http://arxiv.org/pdf/1906.07858](http://arxiv.org/pdf/1906.07858)

