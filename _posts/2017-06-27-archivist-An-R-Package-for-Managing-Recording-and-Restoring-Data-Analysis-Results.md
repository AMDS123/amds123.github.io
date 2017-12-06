---
layout: post
title: "archivist: An R Package for Managing, Recording and Restoring Data Analysis Results"
date: 2017-06-27 12:44:39
categories: arXiv_CV
tags: arXiv_CV Caption
author: Przemyslaw Biecek, Marcin Kosinski
---

* content
{:toc}

##### Abstract
Everything that exists in R is an object [Chambers2016]. This article examines what would be possible if we kept copies of all R objects that have ever been created. Not only objects but also their properties, meta-data, relations with other objects and information about context in which they were created. We introduce archivist, an R package designed to improve the management of results of data analysis. Key functionalities of this package include: (i) management of local and remote repositories which contain R objects and their meta-data (objects' properties and relations between them); (ii) archiving R objects to repositories; (iii) sharing and retrieving objects (and it's pedigree) by their unique hooks; (iv) searching for objects with specific properties or relations to other objects; (v) verification of object's identity and context of it's creation. The presented archivist package extends, in a combination with packages such as knitr and Sweave, the reproducible research paradigm by creating new ways to retrieve and validate previously calculated objects. These new features give a variety of opportunities such as: sharing R objects within reports or articles; adding hooks to R objects in table or figure captions; interactive exploration of object repositories; caching function calls with their results; retrieving object's pedigree (information about how the object was created); automated tracking of the performance of considered models, restoring R libraries to the state in which object was archived.

##### Abstract (translated by Google)
R中存在的所有东西都是一个对象[Chambers2016]。本文将检查如果我们保存了所有创建的R对象的副本，那么这将是可能的。不仅是对象，还有它们的属性，元数据，与其他对象的关系以及关于创建它们的上下文的信息。我们引入档案管理员，一个R包，旨在改善数据分析结果的管理。这个软件包的关键功能包括：（i）管理包含R对象及其元数据（对象的属性及其关系）的本地和远程存储库; （ii）将R对象存档到存储库; （三）通过独特的钩子共享和检索对象（和它的血统）; （iv）搜索具有特定属性或与其他对象的关系的对象; （v）验证对象的身份和创建的上下文。提供的档案文件包通过与诸如knitr和Sweave等软件包的组合，扩展了可重复的研究范式，通过创建新的方法来检索和验证先前计算的对象。这些新功能提供了各种机会，如：在报告或文章中共享R对象;在表格或图形标题中为R对象添加钩子;对象库的交互式探索;缓存函数调用的结果;检索对象的血统（有关对象如何创建的信息）;自动跟踪所考虑的模型的性能，将R库恢复到对象归档状态。

##### URL
[https://arxiv.org/abs/1706.08822](https://arxiv.org/abs/1706.08822)

