---
layout: post
title: "From narrative descriptions to MedDRA: automagically encoding adverse drug reactions"
date: 2016-12-12 16:14:02
categories: arXiv_CL
tags: arXiv_CL Review Detection
author: Carlo Combi, Margherita Zorzi, Gabriele Pozzani, Ugo Moretti
mathjax: true
---

* content
{:toc}

##### Abstract
The collection of narrative spontaneous reports is an irreplaceable source for the prompt detection of suspected adverse drug reactions (ADRs): qualified domain experts manually revise a huge amount of narrative descriptions and then encode texts according to MedDRA standard terminology. The manual annotation of narrative documents with medical terminology is a subtle and expensive task, since the number of reports is growing up day-by-day. MagiCoder, a Natural Language Processing algorithm, is proposed for the automatic encoding of free-text descriptions into MedDRA terms. MagiCoder procedure is efficient in terms of computational complexity (in particular, it is linear in the size of the narrative input and the terminology). We tested it on a large dataset of about 4500 manually revised reports, by performing an automated comparison between human and MagiCoder revisions. For the current base version of MagiCoder, we measured: on short descriptions, an average recall of $86\%$ and an average precision of $88\%$; on medium-long descriptions (up to 255 characters), an average recall of $64\%$ and an average precision of $63\%$. From a practical point of view, MagiCoder reduces the time required for encoding ADR reports. Pharmacologists have simply to review and validate the MagiCoder terms proposed by the application, instead of choosing the right terms among the 70K low level terms of MedDRA. Such improvement in the efficiency of pharmacologists' work has a relevant impact also on the quality of the subsequent data analysis. We developed MagiCoder for the Italian pharmacovigilance language. However, our proposal is based on a general approach, not depending on the considered language nor the term dictionary.

##### Abstract (translated by Google)
叙述式自发报告的收集是及时发现疑似不良反应（ADR）的不可替代的来源：合格的领域专家手动修订大量叙述性描述，然后根据MedDRA标准术语对文本进行编码。用医学术语对叙述性文件进行手工标注是一个微妙和昂贵的任务，因为报告的数量正在日益增加。 MagiCoder是一种自然语言处理算法，用于将自由文本描述自动编码为MedDRA术语。 MagiCoder程序在计算复杂性方面是高效的（尤其是叙述输入和术语的大小是线性的）。我们通过在人类和MagiCoder修订之间进行自动比较，在大约4500个手动修改的报告的大型数据集上进行测试。对于目前的MagiCoder基本版本，我们测量：在简短的描述中，平均回忆为$ 86 \％$，平均精确度为$ 88 \％$;在中长期的描述（最多255个字符），平均回忆$ 64 \％$，平均精确度$ 63 \％$。从实际的角度来看，MagiCoder减少了编码ADR报告所需的时间。药理学家只需要审查和验证申请提出的MagiCoder术语，而不是在MedDRA的70K低端术语中选择正确的术语。药理学家工作效率的提高也对后续数据分析的质量有着相关的影响。我们为意大利药物警戒语言开发了MagiCoder。但是，我们的建议是基于一般的方法，不依赖于所考虑的语言或词典。

##### URL
[https://arxiv.org/abs/1612.03762](https://arxiv.org/abs/1612.03762)

##### PDF
[https://arxiv.org/pdf/1612.03762](https://arxiv.org/pdf/1612.03762)

