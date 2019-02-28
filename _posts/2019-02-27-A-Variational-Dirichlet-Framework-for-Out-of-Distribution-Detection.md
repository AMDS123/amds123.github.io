---
layout: post
title: "A Variational Dirichlet Framework for Out-of-Distribution Detection"
date: 2019-02-27 01:51:41
categories: arXiv_AI
tags: arXiv_AI Adversarial Inference Deep_Learning Detection
author: Wenhu Chen, Yilin Shen, Hongxia Jin, William Wang
mathjax: true
---

* content
{:toc}

##### Abstract
With the recently rapid development in deep learning, deep neural networks have been widely adopted in many real-life applications. However, deep neural networks are also known to have very little control over its uncertainty for unseen examples, which potentially causes very harmful and annoying consequences in practical scenarios. In this paper, we are particularly interested in designing a higher-order uncertainty metric for deep neural networks and investigate its effectiveness under the out-of-distribution detection task proposed by~\cite{hendrycks2016baseline}. Our method first assumes there exists an underlying higher-order distribution $\mathbb{P}(z)$, which controls label-wise categorical distribution $\mathbb{P}(y)$ over classes on the K-dimension simplex, and then approximate such higher-order distribution via parameterized posterior function $p_{\theta}(z|x)$ under variational inference framework, finally we use the entropy of learned posterior distribution $p_{\theta}(z|x)$ as uncertainty measure to detect out-of-distribution examples. Further, we propose an auxiliary objective function to discriminate against synthesized adversarial examples to further increase the robustness of the proposed uncertainty measure. Through comprehensive experiments on various datasets, our proposed framework is demonstrated to consistently outperform competing algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07308](http://arxiv.org/abs/1811.07308)

##### PDF
[http://arxiv.org/pdf/1811.07308](http://arxiv.org/pdf/1811.07308)

