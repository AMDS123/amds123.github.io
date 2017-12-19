---
layout: post
title: "Normalization of Relative and Incomplete Temporal Expressions in Clinical Narratives"
date: 2015-10-16 18:35:13
categories: arXiv_CL
tags: arXiv_CL Classification Relation
author: Weiyi Sun, Anna Rumshisky, Ozlem Uzuner
mathjax: true
---

* content
{:toc}

##### Abstract
We analyze the RI-TIMEXes in temporally annotated corpora and propose two hypotheses regarding the normalization of RI-TIMEXes in the clinical narrative domain: the anchor point hypothesis and the anchor relation hypothesis. We annotate the RI-TIMEXes in three corpora to study the characteristics of RI-TMEXes in different domains. This informed the design of our RI-TIMEX normalization system for the clinical domain, which consists of an anchor point classifier, an anchor relation classifier and a rule-based RI-TIMEX text span parser. We experiment with different feature sets and perform error analysis for each system component. The annotation confirmed the hypotheses that we can simplify the RI-TIMEXes normalization task using two multi-label classifiers. Our system achieves anchor point classification, anchor relation classification and rule-based parsing accuracy of 74.68%, 87.71% and 57.2% (82.09% under relaxed matching criteria) respectively on the held-out test set of the 2012 i2b2 temporal relation challenge. Experiments with feature sets reveals some interesting findings such as the verbal tense feature does not inform the anchor relation classification in clinical narratives as much as the tokens near the RI-TIMEX. Error analysis shows that underrepresented anchor point and anchor relation classes are difficult to detect. We formulate the RI-TIMEX normalization problem as a pair of multi-label classification problems. Considering only the RI-TIMEX extraction and normalization, the system achieves statistically significant improvement over the RI-TIMEX results of the best systems in the 2012 i2b2 challenge.

##### Abstract (translated by Google)
我们分析时间注释语料库中的RI-TIMEX，并提出关于RI-TIMEX在临床叙述领域中的归一化的两个假设：定位点假说和定位关系假说。我们在三个语料中注释了RI-TIMEX，以研究不同领域的RI-TMEX的特点。这通知了我们的RI-TIMEX归一化系统的临床领域的设计，其中包括一个锚点分类器，一个锚定关系分类器和一个基于规则的RI-TIMEX文本跨度分析器。我们试验不同的功能集，并对每个系统组件进行错误分析。注释证实了我们可以使用两个多标签分类器简化RI-TIMEXes标准化任务的假设。我们的系统在2012年i2b2时间关系挑战的测试集上分别实现了锚点分类，锚定关系分类和基于规则的解析精度分别为74.68％，87.71％和57.2％（松弛匹配标准下的82.09％）。功能集的实验揭示了一些有趣的发现，如言语时态特征不像RI-TIMEX附近的令牌那样通知临床叙述中的锚关系分类。错误分析表明，代表性不足的锚点和锚点关系类很难被发现。我们将RI-TIMEX归一化问题制定为一对多标签分类问题。仅考虑RI-TIMEX提取和归一化，与2012年i2b2挑战中最佳系统的RI-TIMEX结果相比，该系统的统计显着改善。

##### URL
[https://arxiv.org/abs/1510.04972](https://arxiv.org/abs/1510.04972)

##### PDF
[https://arxiv.org/pdf/1510.04972](https://arxiv.org/pdf/1510.04972)

