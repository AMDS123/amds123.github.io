---
layout: post
title: "Improve Diverse Text Generation by Self Labeling Conditional Variational Auto Encoder"
date: 2019-03-26 12:53:26
categories: arXiv_CL
tags: arXiv_CL Text_Generation
author: Yuchi Zhang, Yongliang Wang, Liping Zhang, Zhiqiang Zhang, Kun Gai
mathjax: true
---

* content
{:toc}

##### Abstract
Diversity plays a vital role in many text generating applications. In recent years, Conditional Variational Auto Encoders (CVAE) have shown promising performances for this task. However, they often encounter the so called KL-Vanishing problem. Previous works mitigated such problem by heuristic methods such as strengthening the encoder or weakening the decoder while optimizing the CVAE objective function. Nevertheless, the optimizing direction of these methods are implicit and it is hard to find an appropriate degree to which these methods should be applied. In this paper, we propose an explicit optimizing objective to complement the CVAE to directly pull away from KL-vanishing. In fact, this objective term guides the encoder towards the "best encoder" of the decoder to enhance the expressiveness. A labeling network is introduced to estimate the "best encoder". It provides a continuous label in the latent space of CVAE to help build a close connection between latent variables and targets. The whole proposed method is named Self Labeling CVAE~(SLCVAE). To accelerate the research of diverse text generation, we also propose a large native one-to-many dataset. Extensive experiments are conducted on two tasks, which show that our method largely improves the generating diversity while achieving comparable accuracy compared with state-of-art algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10842](http://arxiv.org/abs/1903.10842)

##### PDF
[http://arxiv.org/pdf/1903.10842](http://arxiv.org/pdf/1903.10842)

