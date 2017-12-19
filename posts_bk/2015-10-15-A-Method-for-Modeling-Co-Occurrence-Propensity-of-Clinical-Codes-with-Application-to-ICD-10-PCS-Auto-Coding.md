---
layout: post
title: "A Method for Modeling Co-Occurrence Propensity of Clinical Codes with Application to ICD-10-PCS Auto-Coding"
date: 2015-10-15 22:36:08
categories: arXiv_CL
tags: arXiv_CL
author: Michael Subotin, Anthony R. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Objective. Natural language processing methods for medical auto-coding, or automatic generation of medical billing codes from electronic health records, generally assign each code independently of the others. They may thus assign codes for closely related procedures or diagnoses to the same document, even when they do not tend to occur together in practice, simply because the right choice can be difficult to infer from the clinical narrative. Materials and Methods. We propose a method that injects awareness of the propensities for code co-occurrence into this process. First, a model is trained to estimate the conditional probability that one code is assigned by a human coder, given than another code is known to have been assigned to the same document. Then, at runtime, an iterative algorithm is used to apply this model to the output of an existing statistical auto-coder to modify the confidence scores of the codes. Results. We tested this method in combination with a primary auto-coder for ICD-10 procedure codes, achieving a 12% relative improvement in F-score over the primary auto-coder baseline. Discussion. The proposed method can be used, with appropriate features, in combination with any auto-coder that generates codes with different levels of confidence. Conclusion. The promising results obtained for ICD-10 procedure codes suggest that the proposed method may have wider applications in auto-coding.

##### Abstract (translated by Google)
目的。用于医疗自动编码的自然语言处理方法或从电子健康记录自动生成医疗帐单代码通常将每个代码独立于其他代码分配。因此，即使他们不倾向于在实践中一起出现，他们也可能为相同的文件分配密切相关的程序或诊断的代码，仅仅因为正确的选择可能难以从临床叙述中推断出来。材料和方法。我们提出了一种方法，注意代码共现的倾向到这个过程中的意识。首先，训练一个模型来估计一个代码由一个人类编码器分配的条件概率，而另一个代码已知被分配给同一个文档。然后，在运行时，使用迭代算法将该模型应用于现有统计自动编码器的输出以修改代码的置信度分数。结果。我们将此方法与ICD-10程序代码的主要自动编码器相结合进行了测试，与主要自动编码器基线相比，实现了F-score相对改善12％。讨论。所提出的方法可以与具有适当特征的任何自动编码器结合使用，其产生具有不同置信水平的代码。结论。对于ICD-10程序代码所获得的有希望的结果表明，所提出的方法可能在自动编码中具有更广泛的应用。

##### URL
[https://arxiv.org/abs/1510.04734](https://arxiv.org/abs/1510.04734)

##### PDF
[https://arxiv.org/pdf/1510.04734](https://arxiv.org/pdf/1510.04734)

