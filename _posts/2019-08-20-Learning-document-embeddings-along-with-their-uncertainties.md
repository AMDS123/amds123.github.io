---
layout: post
title: "Learning document embeddings along with their uncertainties"
date: 2019-08-20 20:31:51
categories: arXiv_CL
tags: arXiv_CL Embedding Inference
author: Santosh Kesiraju, Old&#x159;ich Plchot, Luka&#x161; Burget, Suryakanth V Gangashetty
mathjax: true
---

* content
{:toc}

##### Abstract
Majority of the text modelling techniques yield only point estimates of document embeddings and lack in capturing the uncertainty of the estimates. These uncertainties give a notion of how well the embeddings represent a document. We present Bayesian subspace multinomial model (Bayesian SMM), a generative log-linear model that learns to represent documents in the form of Gaussian distributions, thereby encoding the uncertainty in its covariance. Additionally, in the proposed Bayesian SMM, we address a commonly encountered problem of intractability that appears during variational inference in mixed-logit models. We also present a generative Gaussian linear classifier for topic identification that exploits the uncertainty in document embeddings. Our intrinsic evaluation using perplexity measure shows that the proposed Bayesian SMM fits the data better as compared to variational auto-encoder based document model. Our topic identification experiments on speech (Fisher) and text (20Newsgroups) corpora show that the proposed Bayesian SMM is robust to over-fitting on unseen test data. The topic ID results show that the proposed model is significantly better than variational auto-encoder based methods and achieve similar results when compared to fully supervised discriminative models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07599](http://arxiv.org/abs/1908.07599)

##### PDF
[http://arxiv.org/pdf/1908.07599](http://arxiv.org/pdf/1908.07599)

