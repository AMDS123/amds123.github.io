---
layout: post
title: "Interactive in-base street model edit: how common GIS software and a database can serve as a custom Graphical User Interface"
date: 2018-01-17 18:55:43
categories: arXiv_CV
tags: arXiv_CV GAN Face
author: Remi Cura, Julien Perret, Nicolas Paparoditis
mathjax: true
---

* content
{:toc}

##### Abstract
Our modern world produces an increasing quantity of data, and especially geospatial data, with advance of sensing technologies, and growing complexity and organisation of vector data. Tools are needed to efficiently create and edit those vector geospatial data. Procedural generation has been a tool of choice to generate strongly organised data, yet it may be hard to control. Because those data may be involved to take consequence-full real life decisions, user interactions are required to check data and edit it. The classical process to do so would be to build an adhoc Graphical User Interface (GUI) tool adapted for the model and method being used. This task is difficult, takes a large amount of resources, and is very specific to one model, making it hard to share and re-use. 
 Besides, many common generic GUI already exists to edit vector data, each having its specialities. We propose a change of paradigm; instead of building a specific tool for one task, we use common GIS software as GUIs, and deport the specific interactions from the software to within the database. In this paradigm, GIS software simply modify geometry and attributes of database layers, and those changes are used by the database to perform automated task. 
 This new paradigm has many advantages. The first one is genericity. With in-base interaction, any GIS software can be used to perform edition, whatever the software is a Desktop sofware or a web application. The second is concurrency and coherency. Because interaction is in-base, use of database features allows seamless multi-user work, and can guarantee that the data is in a coherent state. Last we propose tools to facilitate multi-user edits, both during the edit phase (each user knows what areas are edited by other users), and before and after edit (planning of edit, analyse of edited areas).

##### Abstract (translated by Google)
我们的现代世界产生越来越多的数据，特别是地理空间数据，随着传感技术的进步，以及矢量数据的复杂性和组织的增加。需要工具来有效地创建和编辑这些矢量地理空间数据。程序生成一直是生成组织严密的数据的首选工具，但它可能很难控制。由于这些数据可能涉及到后果完全的现实生活的决定，所以需要用户交互来检查数据并对其进行编辑。这样做的经典过程将是建立一个适合所使用的模型和方法的专门的图形用户界面（GUI）工具。这个任务是困难的，需要大量的资源，而且对一个模型非常具体，难以共享和重复使用。
 另外，还有许多通用的通用图形用户界面已经存在来编辑矢量数据，每一个都有它的专长我们提出一个范式的改变;我们不是为一个任务建立特定的工具，而是使用常见的GIS软件作为GUI，并将特定的交互从软件驱逐到数据库中。在这个范例中，GIS软件只是修改数据库层的几何和属性，而这些更改被数据库用来执行自动化任务。
 这种新的范式有很多优点。第一个是通用性。通过基于内部的交互，无论软件是桌面软件还是Web应用程序，任何GIS软件都可用于执行编辑。其次是并发性和一致性。由于交互是基于内部的，因此使用数据库功能可以实现无缝的多用户工作，并且可以保证数据处于一致状态。最后，我们提出了在编辑阶段（每个用户知道其他用户编辑哪些区域）以及编辑之前和之后（编辑计划，编辑区域分析）的多用户编辑工具。

##### URL
[http://arxiv.org/abs/1801.05800](http://arxiv.org/abs/1801.05800)

##### PDF
[http://arxiv.org/pdf/1801.05800](http://arxiv.org/pdf/1801.05800)

