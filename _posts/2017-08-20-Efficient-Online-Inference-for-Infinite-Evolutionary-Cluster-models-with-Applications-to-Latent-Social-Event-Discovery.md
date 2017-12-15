---
layout: post
title: "Efficient Online Inference for Infinite Evolutionary Cluster models with Applications to Latent Social Event Discovery"
date: 2017-08-20 18:17:27
categories: arXiv_CL
tags: arXiv_CL Inference
author: Wei Wei, Kennth Joseph, Kathleen Carley
mathjax: true
---

* content
{:toc}

##### Abstract
The Recurrent Chinese Restaurant Process (RCRP) is a powerful statistical method for modeling evolving clusters in large scale social media data. With the RCRP, one can allow both the number of clusters and the cluster parameters in a model to change over time. However, application of the RCRP has largely been limited due to the non-conjugacy between the cluster evolutionary priors and the Multinomial likelihood. This non-conjugacy makes inference di cult and restricts the scalability of models which use the RCRP, leading to the RCRP being applied only in simple problems, such as those that can be approximated by a single Gaussian emission. In this paper, we provide a novel solution for the non-conjugacy issues for the RCRP and an example of how to leverage our solution for one speci c problem - the social event discovery problem. By utilizing Sequential Monte Carlo methods in inference, our approach can be massively paralleled and is highly scalable, to the extent it can work on tens of millions of documents. We are able to generate high quality topical and location distributions of the clusters that can be directly interpreted as real social events, and our experimental results suggest that the approaches proposed achieve much better predictive performance than techniques reported in prior work. We also demonstrate how the techniques we develop can be used in a much more general ways toward similar problems.

##### Abstract (translated by Google)
经常性中餐馆过程（RCRP）是一种强大的统计方法，用于对大规模社交媒体数据中的演变群集进行建模。使用RCRP，可以允许模型中的聚类数量和聚类参数随时间变化。然而，由于聚类演化先验和多项式可能性之间的非共轭性，RCRP的应用在很大程度上受到限制。这种非共轭使得推断困难并且限制了使用RCRP的模型的可扩展性，导致RCRP仅被应用于简单的问题，诸如可以通过单个高斯发射近似的那些问题。在本文中，我们为RCRP的非共轭问题提供了一个新的解决方案，以及如何利用我们的解决方案来解决一个特定问题 - 社交事件发现问题的例子。通过在推理中使用顺序蒙特卡罗方法，我们的方法可以大规模并行，并且具有高度可扩展性，能够处理数千万个文档。我们能够产生集群的高质量的局部和位置分布，可以直接解释为真实的社会事件，我们的实验结果表明，提出的方法比之前的工作报告的技术有更好的预测性能。我们也展示了我们开发的技术如何能够以更一般的方式用于类似的问题。

##### URL
[https://arxiv.org/abs/1708.06000](https://arxiv.org/abs/1708.06000)

##### PDF
[https://arxiv.org/pdf/1708.06000](https://arxiv.org/pdf/1708.06000)

