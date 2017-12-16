---
layout: post
title: "A General Framework for the Recognition of Online Handwritten Graphics"
date: 2017-09-19 13:06:32
categories: arXiv_CV
tags: arXiv_CV Relation Recognition
author: Frank Julca-Aguilar, Harold Mouchère, Christian Viard-Gaudin, Nina S. T. Hirata
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new framework for the recognition of online handwritten graphics. Three main features of the framework are its ability to treat symbol and structural level information in an integrated way, its flexibility with respect to different families of graphics, and means to control the tradeoff between recognition effectiveness and computational cost. We model a graphic as a labeled graph generated from a graph grammar. Non-terminal vertices represent subcomponents, terminal vertices represent symbols, and edges represent relations between subcomponents or symbols. We then model the recognition problem as a graph parsing problem: given an input stroke set, we search for a parse tree that represents the best interpretation of the input. Our graph parsing algorithm generates multiple interpretations (consistent with the grammar) and then we extract an optimal interpretation according to a cost function that takes into consideration the likelihood scores of symbols and structures. The parsing algorithm consists in recursively partitioning the stroke set according to structures defined in the grammar and it does not impose constraints present in some previous works (e.g. stroke ordering). By avoiding such constraints and thanks to the powerful representativeness of graphs, our approach can be adapted to the recognition of different graphic notations. We show applications to the recognition of mathematical expressions and flowcharts. Experimentation shows that our method obtains state-of-the-art accuracy in both applications.

##### Abstract (translated by Google)
我们提出了一个新的在线手写图形识别框架。该框架的三个主要特点是它能够综合处理符号和结构层次的信息，它在不同的图形系列方面的灵活性，以及​​控制识别效率和计算成本之间权衡的手段。我们将图形建模为从图形文法生成的标记图形。非终端顶点代表子组件，终端顶点代表符号，边代表子组件或符号之间的关系。然后，我们将识别问题建模为一个图解析问题：给定一个输入描边集合，我们搜索代表输入的最佳解释的解析树。我们的图解析算法生成多重解释（与语法一致），然后根据考虑符号和结构的似然分数的成本函数提取最佳解释。解析算法包括根据语法中定义的结构对笔画集进行递归划分，并且不强加某些以前的作品（例如笔画排序）中存在的约束。通过避免这种限制，并且由于图的强大代表性，我们的方法可以适应不同图形符号的识别。我们展示应用程序来识别数学表达式和流程图。实验表明，我们的方法在两种应用中都获得了最先进的精度。

##### URL
[https://arxiv.org/abs/1709.06389](https://arxiv.org/abs/1709.06389)

##### PDF
[https://arxiv.org/pdf/1709.06389](https://arxiv.org/pdf/1709.06389)

