---
title: 分布式系统
status: Completed
category: 概念
---

## 是什么

分布式系统是通过网络连接的自主计算元素的集合，在用户看来是一个单一的连贯系统。
一般被称为 [节点](/nodes/)，这些组件可以是硬件设备（如电脑、手机）或软件进程。
节点被编程以实现一个共同的目标，为了协作，它们通过网络交换信息。

## 解决的问题

今天的许多现代应用程序都非常大，需要超级计算机来操作。想想Gmail或Netflix。
没有一台计算机强大到足以承载整个应用程序。通过连接多台计算机，计算能力几乎变得无限大。
如果没有分布式计算，我们今天依赖的许多应用就不可能实现。

传统上，系统会纵向 [扩展](/scalability/)。这就是当你在一台单独的机器上添加更多的 CPU 或内存。
垂直扩展很耗时，需要停机，而且很快就会达到极限。

## 如何帮助

分布式系统允许 [水平扩展](/horizontal_scaling/)（例如，在需要时向系统添加更多节点）。这可以是自动化的，允许系统处理工作负荷或资源消耗的突然增加。

非分布式系统面临着故障的风险，因为如果一台机器发生故障，整个系统都会故障。分布式系统可以设计成这样，即使一些机器发生故障，整个系统仍然可以继续工作，产生相同的结果。