---
layout: post
title: "Domain-Independent turn-level Dialogue Quality Evaluation via User Satisfaction Estimation"
date: 2019-08-19 20:58:24
categories: arXiv_AI
tags: arXiv_AI Sparse Relation
author: Praveen Kumar Bodigutla, Longshaokan Wang, Kate Ridgeway, Joshua Levy, Swanand Joshi, Alborz Geramifard, Spyros Matsoukas
mathjax: true
---

* content
{:toc}

##### Abstract
An automated metric to evaluate dialogue quality is vital for optimizing data driven dialogue management. The common approach of relying on explicit user feedback during a conversation is intrusive and sparse. Current models to estimate user satisfaction use limited feature sets and rely on annotation schemes with low inter-rater reliability, limiting generalizability to conversations spanning multiple domains. To address these gaps, we created a new Response Quality annotation scheme, based on which we developed turn-level User Satisfaction metric. We introduced five new domain-independent feature sets and experimented with six machine learning models to estimate the new satisfaction metric. 
 Using Response Quality annotation scheme, across randomly sampled single and multi-turn conversations from 26 domains, we achieved high inter-annotator agreement (Spearman's rho 0.94). The Response Quality labels were highly correlated (0.76) with explicit turn-level user ratings. Gradient boosting regression achieved best correlation of ~0.79 between predicted and annotated user satisfaction labels. Multi Layer Perceptron and Gradient Boosting regression models generalized to an unseen domain better (linear correlation 0.67) than other models. Finally, our ablation study verified that our novel features significantly improved model performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07064](http://arxiv.org/abs/1908.07064)

##### PDF
[http://arxiv.org/pdf/1908.07064](http://arxiv.org/pdf/1908.07064)

