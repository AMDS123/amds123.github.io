---
layout: post
title: "Towards Complex Text-to-SQL in Cross-Domain Database with Intermediate Representation"
date: 2019-05-20 16:44:00
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Jiaqi Guo, Zecheng Zhan, Yan Gao, Yan Xiao, Jian-Guang Lou, Ting Liu, Dongmei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural approach called IRNet for complex and cross-domain Text-to-SQL. IRNet aims to address two challenges: 1) the mismatch between intents expressed in natural language (NL) and the implementation details in SQL; 2) the challenge in predicting columns caused by the large number of out-of-domain words. Instead of end-to-end synthesizing a SQL query, IRNet decomposes the synthesis process into three phases. In the first phase, IRNet performs a schema linking over a question and a database schema. Then, IRNet adopts a grammar-based neural model to synthesize a SemQL query which is an intermediate representation that we design to bridge NL and SQL. Finally, IRNet deterministically infers a SQL query from the synthesized SemQL query with domain knowledge. On the challenging Text-to-SQL benchmark Spider, IRNet achieves 46.7% accuracy, obtaining 19.5% absolute improvement over previous state-of-the-art approaches. At the time of writing, IRNet achieves the first position on the Spider leaderboard.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08205](http://arxiv.org/abs/1905.08205)

##### PDF
[http://arxiv.org/pdf/1905.08205](http://arxiv.org/pdf/1905.08205)

