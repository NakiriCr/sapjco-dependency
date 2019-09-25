# Sapjco Runtime Dependency

**README: [English](https://gitlab.yanzx-dev.cn/sapjco/sapjco-dependency/blob/master/README.md) | [中文](https://gitlab.yanzx-dev.cn/sapjco/sapjco-dependency/blob/master/README-zh.md)**

![Hex.pm](https://img.shields.io/hexpm/l/plug.svg?color=green)
![Maven Central](https://img.shields.io/maven-central/v/com.github.virtualcry/com.sap.conn.jco.sapjco.svg)
![Sonatype Nexus (Snapshots)](https://img.shields.io/nexus/snapshots/https/oss.sonatype.org/com.github.virtualcry/com.sap.conn.jco.sapjco.svg)

## 简介
SAP Java连接器（SAP JCo）是允许Java应用程序与任何SAP系统通信的工具包。
它结合了易于使用的API和前所未有的灵活性和性能。
SAP JCo支持在以下两个方向上与sap服务器进行通信：`入站调用`：Java 到 SAP 以及`出站调用`：SAP 到 Java。


由于以下功能，SAP JCo是构建支持SAP的Java应用程序的最佳选择：
* 高性能基于JNI的`RFC中间件`
* 支持R/3 3.1I及更高版本（以及其他具有BAPI或RFM的SAP组件）
* 支持入站（Java客户端调用BAPI或RFM）和出站（ABAP调用Java服务器）调用
* 支持`同步`，`事务`（对于IDocs很重要）和`RFC队列`.
* 支持客户端连接池（适用于Web服务器）.
* 多平台
* 完整和正确的字节内码处理（包括多字节语言）.
* 易于安装和部署.

## SAP JCo体系结构
![avatar](https://gitlab.yanzx-dev.cn/sapjco/sapjco-dependency/raw/master/images/sapjco-architecture.png)
<br>
SAP 以两种不同的方式提供SAP Java连接器：作为可以独立于SAP系统安装的独立软件组件，或者作为SAP技术组件的集成组件。

## 集成标准方案
* SAP Web应用服务器中的J2EE / ABAP耦合
* SAP JCo方案：SAP BC