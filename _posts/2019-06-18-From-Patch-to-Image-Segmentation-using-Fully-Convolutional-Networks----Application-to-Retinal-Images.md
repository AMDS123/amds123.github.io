---
layout: post
title: "From Patch to Image Segmentation using Fully Convolutional Networks -- Application to Retinal Images"
date: 2019-06-18 11:14:20
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Taibou Birgui Sekou, Moncef Hidane, Julien Olivier, Hubert Cardot
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning based models, generally, require a large number of samples for appropriate training, a requirement that is difficult to satisfy in the medical field. This issue can usually be avoided with a proper initialization of the weights. On the task of medical image segmentation in general, two techniques are oftentimes employed to tackle the training of a deep network $f_T$. The first one consists in reusing some weights of a network $f_S$ pre-trained on a large scale database ($e.g.$ ImageNet). This procedure, also known as $transfer$ $learning$, happens to reduce the flexibility when it comes to new network design since $f_T$ is constrained to match some parts of $f_S$. The second commonly used technique consists in working on image patches to benefit from the large number of available patches. This paper brings together these two techniques and propose to train $arbitrarily$ $designed$ $networks$ that segment an image in one forward pass, with a focus on relatively small databases. An experimental work have been carried out on the tasks of retinal blood vessel segmentation and the optic disc one, using four publicly available databases. Furthermore, three types of network are considered, going from a very light weighted network to a densely connected one. The final results show the efficiency of the proposed framework along with state of the art results on all the databases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03892](http://arxiv.org/abs/1904.03892)

##### PDF
[http://arxiv.org/pdf/1904.03892](http://arxiv.org/pdf/1904.03892)

