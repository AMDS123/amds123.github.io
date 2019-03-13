---
layout: post
title: "Communication-efficient distributed SGD with Sketching"
date: 2019-03-12 17:59:48
categories: arXiv_AI
tags: arXiv_AI
author: Nikita Ivkin, Daniel Rothchild, Enayat Ullah, Vladimir Braverman, Ion Stoica, Raman Arora
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale distributed training of neural networks is often limited by network bandwidth, wherein the communication time overwhelms the local computation time. Motivated by the success of sketching methods in sub-linear/streaming algorithms, we propose a sketching-based approach to minimize the communication costs between nodes without losing accuracy. In our proposed method, workers in a distributed, synchronous training setting send sketches of their gradient vectors to the parameter server instead of the full gradient vector. Leveraging the theoretical properties of sketches, we show that this method recovers the favorable convergence guarantees of single-machine top-$k$ SGD. Furthermore, when applied to a model with $d$ dimensions on $W$ workers, our method requires only $\Theta(kW)$ bytes of communication, compared to $\Omega(dW)$ for vanilla distributed SGD. To validate our method, we run experiments using a residual network trained on the CIFAR-10 dataset. We achieve no drop in validation accuracy with a compression ratio of 4, or about 1 percentage point drop with a compression ratio of 8. We also demonstrate that our method scales to many workers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04488](http://arxiv.org/abs/1903.04488)

##### PDF
[http://arxiv.org/pdf/1903.04488](http://arxiv.org/pdf/1903.04488)

