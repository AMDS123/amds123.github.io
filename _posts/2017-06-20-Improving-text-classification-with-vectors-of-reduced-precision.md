---
layout: post
title: "Improving text classification with vectors of reduced precision"
date: 2017-06-20 11:13:06
categories: arXiv_CL
tags: arXiv_CL Text_Classification Classification
author: Krzysztof Wróbel, Maciej Wielgosz, Marcin Pietroń, Michał Karwatowski, Aleksander Smywiński-Pohl
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents the analysis of the impact of a floating-point number precision reduction on the quality of text classification. The precision reduction of the vectors representing the data (e.g. TF-IDF representation in our case) allows for a decrease of computing time and memory footprint on dedicated hardware platforms. The impact of precision reduction on the classification quality was performed on 5 corpora, using 4 different classifiers. Also, dimensionality reduction was taken into account. Results indicate that the precision reduction improves classification accuracy for most cases (up to 25% of error reduction). In general, the reduction from 64 to 4 bits gives the best scores and ensures that the results will not be worse than with the full floating-point representation.

##### Abstract (translated by Google)
本文介绍了浮点数精度降低对文本分类质量影响的分析。表示数据的矢量（例如在我们的例子中的TF-IDF表示）的精度降低允许在专用硬件平台上减少计算时间和存储器占用空间。精度降低对分类质量的影响在5个语料库上进行，使用4个不同的分类器。此外，还考虑到降维。结果表明，精度的降低提高了大多数情况下的分类精度（误差降低高达25％）。一般来说，从64位减少到4位给出了最好的分数，并且确保结果不会比全浮点表示更差。

##### URL
[https://arxiv.org/abs/1706.06363](https://arxiv.org/abs/1706.06363)

##### PDF
[https://arxiv.org/pdf/1706.06363](https://arxiv.org/pdf/1706.06363)

