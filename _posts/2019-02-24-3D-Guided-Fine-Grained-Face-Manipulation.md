---
layout: post
title: "3D Guided Fine-Grained Face Manipulation"
date: 2019-02-24 06:47:45
categories: arXiv_CV
tags: arXiv_CV Face Quantitative
author: Zhenglin Geng, Chen Cao, Sergey Tulyakov
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for fine-grained face manipulation. Given a face image with an arbitrary expression, our method can synthesize another arbitrary expression by the same person. This is achieved by first fitting a 3D face model and then disentangling the face into a texture and a shape. We then learn different networks in these two spaces. In the texture space, we use a conditional generative network to change the appearance, and carefully design input formats and loss functions to achieve the best results. In the shape space, we use a fully connected network to predict the accurate shapes and use the available depth data for supervision. Both networks are conditioned on expression coefficients rather than discrete labels, allowing us to generate an unlimited amount of expressions. We show the superiority of this disentangling approach through both quantitative and qualitative studies. In a user study, our method is preferred in 85% of cases when compared to the most recent work. When compared to the ground truth, annotators cannot reliably distinguish between our synthesized images and real images, preferring our method in 53% of the cases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08900](http://arxiv.org/abs/1902.08900)

##### PDF
[http://arxiv.org/pdf/1902.08900](http://arxiv.org/pdf/1902.08900)

