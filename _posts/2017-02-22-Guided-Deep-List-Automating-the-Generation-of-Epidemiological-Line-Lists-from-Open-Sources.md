---
layout: post
title: "Guided Deep List: Automating the Generation of Epidemiological Line Lists from Open Sources"
date: 2017-02-22 03:14:36
categories: arXiv_SD
tags: arXiv_SD Inference Language_Model
author: Saurav Ghosh, Prithwish Chakraborty, Bryan L. Lewis, Maimuna S. Majumder, Emily Cohn, John S. Brownstein, Madhav V. Marathe, Naren Ramakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time monitoring and responses to emerging public health threats rely on the availability of timely surveillance data. During the early stages of an epidemic, the ready availability of line lists with detailed tabular information about laboratory-confirmed cases can assist epidemiologists in making reliable inferences and forecasts. Such inferences are crucial to understand the epidemiology of a specific disease early enough to stop or control the outbreak. However, construction of such line lists requires considerable human supervision and therefore, difficult to generate in real-time. In this paper, we motivate Guided Deep List, the first tool for building automated line lists (in near real-time) from open source reports of emerging disease outbreaks. Specifically, we focus on deriving epidemiological characteristics of an emerging disease and the affected population from reports of illness. Guided Deep List uses distributed vector representations (ala word2vec) to discover a set of indicators for each line list feature. This discovery of indicators is followed by the use of dependency parsing based techniques for final extraction in tabular form. We evaluate the performance of Guided Deep List against a human annotated line list provided by HealthMap corresponding to MERS outbreaks in Saudi Arabia. We demonstrate that Guided Deep List extracts line list features with increased accuracy compared to a baseline method. We further show how these automatically extracted line list features can be used for making epidemiological inferences, such as inferring demographics and symptoms-to-hospitalization period of affected individuals.

##### Abstract (translated by Google)
实时监测和应对新出现的公共卫生威胁依赖于及时监测数据的可用性。在流行病的早期阶段，随时可以获得有关实验室确诊病例的详细表格信息，可以帮助流行病学家做出可靠的推断和预测。这种推论对于早日了解某种特定疾病的流行病学至关重要，足以阻止或控制疾病暴发。然而，建立这样的线路表需要相当大的人力监督，因此难以实时生成。在本文中，我们激励引导式深度列表（第一个工具，用于近乎实时地从关于新发疾病暴发的开源报告中构建自动化行列表）。具体而言，我们着重从疾病报告中推断新发疾病和受影响人群的流行病学特征。引导式深度列表使用分布式矢量表示（ala word2vec）来发现每个行列表功能的一组指标。指标的发现之后是使用基于依赖分析的技术以表格形式进行最终提取。我们根据HealthMap提供的与沙特阿拉伯MERS爆发相对应的人类注释线列表评估引导深入列表的表现。我们证明，与基线方法相比，引导深入列表提取的线列表功能具有更高的准确性。我们进一步展示了如何使用这些自动提取的行列表特征来进行流行病学推断，例如推断受影响个体的人口统计学和症状到住院期。

##### URL
[https://arxiv.org/abs/1702.06663](https://arxiv.org/abs/1702.06663)

##### PDF
[https://arxiv.org/pdf/1702.06663](https://arxiv.org/pdf/1702.06663)

