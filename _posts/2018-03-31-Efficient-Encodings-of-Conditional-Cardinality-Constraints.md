---
layout: post
title: "Efficient Encodings of Conditional Cardinality Constraints"
date: 2018-03-31 20:29:07
categories: arXiv_AI
tags: arXiv_AI
author: Abdelhamid Boudane, Said Jabbour, Badran Raddaoui, Lakhdar Sais
mathjax: true
---

* content
{:toc}

##### Abstract
In the encoding of many real-world problems to propositional satisfiability, the cardinality constraint is a recurrent constraint that needs to be managed effectively. Several efficient encodings have been proposed while missing that such a constraint can be involved in a more general propositional formulation. To avoid combinatorial explosion, Tseitin principle usually used to translate such general propositional formula to Conjunctive Normal Form (CNF), introduces fresh propositional variables to represent sub-formulas and/or complex contraints. Thanks to Plaisted and Greenbaum improvement, the polarity of the sub-formula $\Phi$ is taken into account leading to conditional constraints of the form $y\rightarrow \Phi$, or $\Phi\rightarrow y$, where $y$ is a fresh propositional variable. In the case where $\Phi$ represents a cardinality constraint, such translation leads to conditional cardinality constraints subject of the present paper. We first show that when all the clauses encoding the cardinality constraint are augmented with an additional new variable, most of the well-known encodings cease to maintain the generalized arc consistency property. Then, we consider some of these encodings and show how they can be extended to recover such important property. An experimental validation is conducted on a SAT-based pattern mining application, where such conditional cardinality constraints is a cornerstone, showing the relevance of our proposed approach.

##### Abstract (translated by Google)
在将许多现实世界问题编码为命题可满足性时，基数约束是需要有效管理的经常性约束。已经提出了几种有效的编码，但是却错过了这种约束可能涉及更一般的命题式。为了避免组合爆炸，通常使用Tseitin原理将这种一般命题公式转换为Conjunctive Normal Form（CNF），引入新的命题变量来表示子公式和/或复杂的约束条件。由于Plaisted和Greenbaum改进，子公式$ \ Phi $的极性被考虑，导致形式为$ y \ rightarrow \ Phi $或$ \ Phi \ rightarrow y $的条件约束，其中$ y $是一个新的命题变量。在$ \ Phi $表示基数约束的情况下，这样的翻译导致本文的条件基数约束主题。我们首先证明，当编码基数约束的所有子句都增加了一个附加的新变量时，大多数已知的编码就不再保持广义的弧一致性属性。然后，我们考虑一些这些编码，并展示如何扩展它们以恢复这样的重要属性。对基于SAT的模式挖掘应用进行实验验证，其中这种条件基数约束是基石，显示了我们提出的方法的相关性。

##### URL
[http://arxiv.org/abs/1804.00211](http://arxiv.org/abs/1804.00211)

##### PDF
[http://arxiv.org/pdf/1804.00211](http://arxiv.org/pdf/1804.00211)

