---
layout: post
title: "STAR: Spatio-Temporal Altimeter Waveform Retracking using Sparse Representation and Conditional Random Fields"
date: 2017-09-22 10:32:35
categories: arXiv_CV
tags: arXiv_CV Sparse GAN Face Tracking Detection
author: Ribana Roscher, Bernd Uebbing, Jürgen Kusche
mathjax: true
---

* content
{:toc}

##### Abstract
Satellite radar altimetry is one of the most powerful techniques for measuring sea surface height variations, with applications ranging from operational oceanography to climate research. Over open oceans, altimeter return waveforms generally correspond to the Brown model, and by inversion, estimated shape parameters provide mean surface height and wind speed. However, in coastal areas or over inland waters, the waveform shape is often distorted by land influence, resulting in peaks or fast decaying trailing edges. As a result, derived sea surface heights are then less accurate and waveforms need to be reprocessed by sophisticated algorithms. To this end, this work suggests a novel Spatio-Temporal Altimetry Retracking (STAR) technique. We show that STAR enables the derivation of sea surface heights over the open ocean as well as over coastal regions of at least the same quality as compared to existing retracking methods, but for a larger number of cycles and thus retaining more useful data. Novel elements of our method are (a) integrating information from spatially and temporally neighboring waveforms through a conditional random field approach, (b) sub-waveform detection, where relevant sub-waveforms are separated from corrupted or non-relevant parts through a sparse representation approach, and (c) identifying the final best set of sea surfaces heights from multiple likely heights using Dijkstra's algorithm. We apply STAR to data from the Jason-1, Jason-2 and Envisat missions for study sites in the Gulf of Trieste, Italy and in the coastal region of the Ganges-Brahmaputra-Meghna estuary, Bangladesh. We compare to several established and recent retracking methods, as well as to tide gauge data. Our experiments suggest that the obtained sea surface heights are significantly less affected by outliers when compared to results obtained by other approaches.

##### Abstract (translated by Google)
卫星雷达高度测量是测量海面高度变化的最强大的技术之一，应用范围从业务海洋学到气候研究。在开放的海洋上，高度计返回波形通常对应于Brown模型，并且通过反演，估计的形状参数提供平均表面高度和风速。但是，在沿海地区或内陆水域，由于地面影响，波形的形状往往是扭曲的，导致后缘出现峰值或快速衰减。因此，得出的海面高度较不准确，波形需要通过复杂的算法进行重新处理。为此，这项工作提出了一种新颖的空间时间重测（STAR）技术。我们显示，STAR能够推导出海洋表面高度超过开阔海洋以及沿海地区至少与现有的重新研究方法相同的质量，但对于更多的周期数，从而保留更有用的数据。 （a）通过条件随机场方法整合来自空间和时间相邻波形的信息，（b）子波形检测，其中相关的子波形通过稀疏表示与损坏或不相关的部分分开（c）使用Dijkstra算法从多个可能的高度确定最佳的海面高度集合。我们将STAR应用于来自意大利的里雅斯特湾研究点的Jason-1，Jason-2和Envisat任务以及孟加拉国恒河 - 雅鲁藏布江 - 梅赫纳河口沿海地区的数据。我们比较几个既定的和最近的重新研究方法，以及潮测量数据。我们的实验表明，与其他方法所获得的结果相比，获得的海面高度受异常值的影响要小得多。

##### URL
[https://arxiv.org/abs/1709.07681](https://arxiv.org/abs/1709.07681)

##### PDF
[https://arxiv.org/pdf/1709.07681](https://arxiv.org/pdf/1709.07681)

