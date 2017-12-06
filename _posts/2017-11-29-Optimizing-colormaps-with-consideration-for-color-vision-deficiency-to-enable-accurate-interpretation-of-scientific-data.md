---
layout: post
title: 'Optimizing colormaps with consideration for color vision deficiency to enable accurate interpretation of scientific data'
date: 2017-11-29 20:24:15
categories: arXiv_CV
tags: arXiv_CV
author: Jamie R. Nuñez, Chris R. Anderton, Ryan S. Renslow
---

* content
{:toc}

##### Abstract
Color vision deficiency (CVD) affects 8.5% of the population and leads to a different visual perception of colors. Though this has been known for decades, colormaps with many colors across the visual spectra are often used to represent data, leading to the potential for misinterpretation or difficulty with interpretation by someone with this deficiency. Until the creation of the module presented here, there were no colormaps mathematically optimized for CVD using modern color appearance models. While there have been some attempts to make aesthetically pleasing or subjectively tolerable colormaps for those with CVD, our goal was to make optimized colormaps for the most accurate perception of scientific data by as many viewers as possible. We developed a Python module, cmaputil, to create CVD-optimized colormaps, which imports colormaps and modifies them to be perceptually uniform in CVD-safe colorspace while linearizing and maximizing the brightness range. The module is made available to the science community to enable others to easily create their own CVD-optimized colormaps. Here, we present an example CVD-optimized colormap created with this module that is optimized for viewing by those without a CVD as well as those with red-green colorblindness. This colormap, cividis, enables nearly-identical visual-data interpretation to both groups, is perceptually uniform in hue and brightness, and increases in brightness linearly.

##### Abstract (translated by Google)
色觉缺陷（CVD）影响8.5％的人口并导致对颜色的不同视觉感受。尽管这已经有数十年的历史，但是在视觉光谱中色彩映射常常被用来表示数据，导致对这种缺陷的解释可能导致曲解或难以解释。在这里介绍的模块创建之前，没有使用现代颜色外观模型对CVD进行数学优化的颜色映射。虽然已经有人尝试为心血管疾病患者制作美观或主观容忍的彩色地图，但是我们的目标是尽可能多地为观众提供最准确的科学数据感知的色彩地图。我们开发了一个Python模块cmaputil来创建CVD优化的色彩映射，这些色彩映射导入色彩映射并将其修改为在CVD安全的色彩空间中感知均匀，同时线性化并最大化亮度范围。该模块提供给科学界，使其他人可以轻松地创建自己的CVD优化色彩地图。在这里，我们介绍一个用这个模块创建的CVD优化的色彩映射表，这个色彩映射表优化了那些没有CVD的观察者以及红绿色盲的观察者。这个色彩表，cividis，使两个组几乎相同的视觉数据解释，在色调和亮度感知均匀，线性亮度增加。

##### URL
[https://arxiv.org/abs/1712.01662](https://arxiv.org/abs/1712.01662)

