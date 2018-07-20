---
layout: post
title: "Visual Domain Adaptation with Manifold Embedded Distribution Alignment"
date: 2018-07-19 06:45:42
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification Quantitative
author: Jindong Wang, Wenjie Feng, Yiqiang Chen, Han Yu, Meiyu Huang, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Visual domain adaptation aims to learn robust classifiers for the target domain by leveraging knowledge from a source domain. Existing methods either attempt to align the cross-domain distributions, or perform manifold subspace learning. However, there are two significant challenges: (1) degenerated feature transformation, which means that distribution alignment is often performed in the original feature space, where feature distortions are hard to overcome. On the other hand, subspace learning is not sufficient to reduce the distribution divergence. (2) unevaluated distribution alignment, which means that existing distribution alignment methods only align the marginal and conditional distributions with equal importance, while they fail to evaluate the different importance of these two distributions in real applications. In this paper, we propose a Manifold Embedded Distribution Alignment (MEDA) approach to address these challenges. MEDA learns a domain-invariant classifier in Grassmann manifold with structural risk minimization, while performing dynamic distribution alignment to quantitatively account for the relative importance of marginal and conditional distributions. To the best of our knowledge, MEDA is the first attempt to perform dynamic distribution alignment for manifold domain adaptation. Extensive experiments demonstrate that MEDA shows significant improvements in classification accuracy compared to state-of-the-art traditional and deep methods.

##### Abstract (translated by Google)
视觉域适应旨在通过利用来自源域的知识来学习目标域的鲁棒分类器。现有方法或者尝试对齐跨域分布，或者执行流形子空间学习。然而，存在两个重大挑战：（1）退化特征变换，这意味着分布对齐通常在原始特征空间中执行，其中特征变形难以克服。另一方面，子空间学习不足以减少分布差异。 （2）未评估的分布对齐，这意味着现有的分布对齐方法仅使边际和条件分布具有相同的重要性，而它们无法评估这两种分布在实际应用中的不同重要性。在本文中，我们提出了一种Manifold嵌入式分布对齐（MEDA）方法来应对这些挑战。 MEDA学习Grassmann流形中的域不变分类器，结构风险最小化，同时执行动态分布对齐，以定量地解释边际和条件分布的相对重要性。据我们所知，MEDA是第一次尝试对多种域适应进行动态分布对齐。大量实验表明，与最先进的传统方法和深层方法相比，MEDA在分类准确性方面有显着提高。

##### URL
[https://arxiv.org/abs/1807.07258](https://arxiv.org/abs/1807.07258)

##### PDF
[https://arxiv.org/pdf/1807.07258](https://arxiv.org/pdf/1807.07258)

