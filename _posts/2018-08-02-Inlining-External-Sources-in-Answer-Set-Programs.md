---
layout: post
title: "Inlining External Sources in Answer Set Programs"
date: 2018-08-02 09:32:20
categories: arXiv_AI
tags: arXiv_AI Face
author: Christoph Redl
mathjax: true
---

* content
{:toc}

##### Abstract
HEX-programs are an extension of answer set programs (ASP) with external sources. To this end, external atoms provide a bidirectional interface between the program and an external source. The traditional evaluation algorithm for HEX-programs is based on guessing truth values of external atoms and verifying them by explicit calls of the external source. The approach was optimized by techniques that reduce the number of necessary verification calls or speed them up, but the remaining external calls are still expensive. In this paper we present an alternative evaluation approach based on inlining of external atoms, motivated by existing but less general approaches for specialized formalisms such as DL-programs. External atoms are then compiled away such that no verification calls are necessary. The approach is implemented in the dlvhex reasoner. Experiments show a significant performance gain. Besides performance improvements, we further exploit inlining for extending previous (semantic) characterizations of program equivalence from ASP to HEX-programs, including those of strong equivalence, uniform equivalence and H, B -equivalence. Finally, based on these equivalence criteria, we characterize also inconsistency of programs wrt. extensions. Since well-known ASP extensions (such as constraint ASP) are special cases of HEX, the results are interesting beyond the particular formalism. Under consideration in Theory and Practice of Logic Programming (TPLP).

##### Abstract (translated by Google)
HEX程序是具有外部源的答案集程序（ASP）的扩展。为此，外部原子在程序和外部源之间提供双向接口。 HEX程序的传统评估算法基于猜测外部原子的真值并通过外部源的显式调用来验证它们。该方法通过减少必要的验证呼叫数量或加速它们的技术进行了优化，但剩余的外部呼叫仍然很昂贵。在本文中，我们提出了一种基于外部原子内联的替代评估方法，其动机是现有的但不太通用的专业形式主义方法，如DL程序。然后编译掉外部原子，这样就不需要验证调用。该方法在dlvhex推理器中实现。实验表明显着的性能提升。除了性能改进之外，我们进一步利用内联来扩展从ASP到HEX程序的程序等效的先前（语义）表征，包括强等价，统一等价和H，B等价的那些。最后，基于这些等价标准，我们还表征了程序的不一致性。扩展。由于众所周知的ASP扩展（例如约束ASP）是HEX的特例，因此结果超出了特定的形式主义。正在考虑逻辑规划理论与实践（TPLP）。

##### URL
[http://arxiv.org/abs/1808.00727](http://arxiv.org/abs/1808.00727)

##### PDF
[http://arxiv.org/pdf/1808.00727](http://arxiv.org/pdf/1808.00727)

