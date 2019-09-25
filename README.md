# Sapjco Runtime Dependency

![Hex.pm](https://img.shields.io/hexpm/l/plug.svg?color=green)
![Maven Central](https://img.shields.io/maven-central/v/com.github.virtualcry/com.sap.conn.jco.sapjco.svg)
![Sonatype Nexus (Snapshots)](https://img.shields.io/nexus/snapshots/https/oss.sonatype.org/com.github.virtualcry/com.sap.conn.jco.sapjco.svg)

## Introduction
The SAP Java Connector (SAP JCo) is a toolkit that allows a Java application to communicate with any SAP System. 
It combines an easy to use API with unprecedented flexibility and performance. 
The SAP JCo supports communication to the sap server in  both directions inbound calls: Java to SAP System as well as outbound calls: SAP System to Java.


The SAP JCo is the best choice for building SAP-enabled Java applications because of the following features:
* High performance JNI-based RFC middleware.
* Supports R/3 3.1I and higher (and other SAP Components that have BAPIs or RFMs).
* Supports inbound (Java client calls BAPI or RFM) and outbound (ABAP calls Java server) calls.
* Supports synchronous, transactional (important for IDocs), and queued RFC.
* Supports client pooling (good for web servers).
* Multi-platform
* Complete and correct code-page handling (incl. multi-byte languages).
* Easy to install and deploy.

## SAP JCo Architecture
SAP provides SAP Java Connector in two different ways: 
as a standalone software component that can be installed independently of the SAP system or  As an integrated component of an SAP technology component.

## Integrated standard scenario
* J2EE/ABAP Coupling in the SAP Web Application Server
* SAP JCo Scenario: SAP BC
