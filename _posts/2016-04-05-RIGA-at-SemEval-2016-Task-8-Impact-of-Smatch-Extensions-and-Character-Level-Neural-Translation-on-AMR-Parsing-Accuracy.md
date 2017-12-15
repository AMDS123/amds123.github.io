---
layout: post
title: "RIGA at SemEval-2016 Task 8: Impact of Smatch Extensions and Character-Level Neural Translation on AMR Parsing Accuracy"
date: 2016-04-05 14:46:18
categories: arXiv_SD
tags: arXiv_SD
author: Guntis Barzdins, Didzis Gosko
mathjax: true
---

* content
{:toc}

##### Abstract
Two extensions to the AMR smatch scoring script are presented. The first extension com-bines the smatch scoring script with the C6.0 rule-based classifier to produce a human-readable report on the error patterns frequency observed in the scored AMR graphs. This first extension results in 4% gain over the state-of-art CAMR baseline parser by adding to it a manually crafted wrapper fixing the identified CAMR parser errors. The second extension combines a per-sentence smatch with an en-semble method for selecting the best AMR graph among the set of AMR graphs for the same sentence. This second modification au-tomatically yields further 0.4% gain when ap-plied to outputs of two nondeterministic AMR parsers: a CAMR+wrapper parser and a novel character-level neural translation AMR parser. For AMR parsing task the character-level neural translation attains surprising 7% gain over the carefully optimized word-level neural translation. Overall, we achieve smatch F1=62% on the SemEval-2016 official scor-ing set and F1=67% on the LDC2015E86 test set.

##### Abstract (translated by Google)
介绍了AMR smatch评分脚本的两个扩展。第一个扩展将smatch评分脚本与C6.0基于规则的分类器组合在一起，以产生关于在评分的AMR图中观察到的错误模式频率的人类可读报告。第一次扩展比现有的CAMR基线解析器增加了4％，增加了一个手工制作的包装，修复了确定的CAMR解析器错误。第二个扩展将每个句子smatch与一个en-semble方法相结合，用于在同一个句子的AMR图集中选择最好的AMR图。这个第二个修改自动产生了两个非确定性AMR解析器的输出时，进一步0.4％的收益：一个CAMR +包装解析器和一个新的字符级神经翻译AMR解析器。对于AMR解析任务，字符级神经翻译比仔细优化的单词级神经翻译获得惊人的7％增益。总的来说，我们在SemEval-2016官方评分组中取得了F1 = 62％的成绩，在LDC2015E86测试组中F1取得了67％的成绩。

##### URL
[https://arxiv.org/abs/1604.01278](https://arxiv.org/abs/1604.01278)

##### PDF
[https://arxiv.org/pdf/1604.01278](https://arxiv.org/pdf/1604.01278)

