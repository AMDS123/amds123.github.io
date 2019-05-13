---
layout: post
title: "The Regression Tsetlin Machine: A Tsetlin Machine for Continuous Output Problems"
date: 2019-05-10 15:05:30
categories: arXiv_AI
tags: arXiv_AI Inference Classification
author: K. Darshana Abeyrathna, Ole-Christoffer Granmo, Lei Jiao, Morten Goodwin
mathjax: true
---

* content
{:toc}

##### Abstract
The recently introduced Tsetlin Machine (TM) has provided competitive pattern classification accuracy in several benchmarks, composing patterns with easy-to-interpret conjunctive clauses in propositional logic. In this paper, we go beyond pattern classification by introducing a new type of TMs, namely, the Regression Tsetlin Machine (RTM). In all brevity, we modify the inner inference mechanism of the TM so that input patterns are transformed into a single continuous output, rather than to distinct categories. We achieve this by: (1) using the conjunctive clauses of the TM to capture arbitrarily complex patterns; (2) mapping these patterns to a continuous output through a novel voting and normalization mechanism; and (3) employing a feedback scheme that updates the TM clauses to minimize the regression error. The feedback scheme uses a new activation probability function that stabilizes the updating of clauses, while the overall system converges towards an accurate input-output mapping. The performance of the proposed approach is evaluated using six different artificial datasets with and without noise. The performance of the RTM is compared with the Classical Tsetlin Machine (CTM) and the Multiclass Tsetlin Machine (MTM). Our empirical results indicate that the RTM obtains the best training and testing results for both noisy and noise-free datasets, with a smaller number of clauses. This, in turn, translates to higher regression accuracy, using significantly less computational resources.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04206](http://arxiv.org/abs/1905.04206)

##### PDF
[http://arxiv.org/pdf/1905.04206](http://arxiv.org/pdf/1905.04206)

