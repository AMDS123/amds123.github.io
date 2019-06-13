---
layout: post
title: "Does BLEU Score Work for Code Migration?"
date: 2019-06-12 02:48:57
categories: arXiv_CL
tags: arXiv_CL Relation
author: Ngoc Tran, Hieu Tran, Son Nguyen, Hoan Nguyen, Tien N. Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Statistical machine translation (SMT) is a fast-growing sub-field of computational linguistics. Until now, the most popular automatic metric to measure the quality of SMT is BiLingual Evaluation Understudy (BLEU) score. Lately, SMT along with the BLEU metric has been applied to a Software Engineering task named code migration. (In)Validating the use of BLEU score could advance the research and development of SMT-based code migration tools. Unfortunately, there is no study to approve or disapprove the use of BLEU score for source code. In this paper, we conducted an empirical study on BLEU score to (in)validate its suitability for the code migration task due to its inability to reflect the semantics of source code. In our work, we use human judgment as the ground truth to measure the semantic correctness of the migrated code. Our empirical study demonstrates that BLEU does not reflect translation quality due to its weak correlation with the semantic correctness of translated code. We provided counter-examples to show that BLEU is ineffective in comparing the translation quality between SMT-based models. Due to BLEU's ineffectiveness for code migration task, we propose an alternative metric RUBY, which considers lexical, syntactical, and semantic representations of source code. We verified that RUBY achieves a higher correlation coefficient with the semantic correctness of migrated code, 0.775 in comparison with 0.583 of BLEU score. We also confirmed the effectiveness of RUBY in reflecting the changes in translation quality of SMT-based translation models. With its advantages, RUBY can be used to evaluate SMT-based code migration models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04903](http://arxiv.org/abs/1906.04903)

##### PDF
[http://arxiv.org/pdf/1906.04903](http://arxiv.org/pdf/1906.04903)

