---
title: "ML Facility-as-a-Service on Kubernetes (FYP / NCP Research)"
excerpt: "Kubernetes-based multi-tenant ML platform using Kubeflow on on-premise bare-metal servers, with LDAP auth and resource quotas.<br/>"
collection: portfolio
---

**Machine Learning Facility-as-a-Service** is a research platform deployed at the National Centre for Physics (NCP – CoE Aitec) and extended as a Final Year Project at PIEAS.

## Overview

This project prototypes a multi-tenant ML platform that allows hosted researchers to run experiments in isolated namespaces with controlled resource allocations, all on on-premise physical servers.

## Technical Stack

- **Orchestration:** Kubernetes, Kubeflow
- **Authentication:** LDAP-backed identity management
- **Resource Management:** CPU/memory quota controls per namespace
- **Big Data Layer:** Apache Hadoop (HDFS, YARN), HBase, ZooKeeper
- **Custom Web App:** Workflow control interface for ML pipeline management

## Key Contributions

- Designed and deployed multi-tenant namespace isolation
- Implemented LDAP authentication integration for secure researcher access
- Configured resource quota controls to prevent over-provisioning
- Contributed to Hadoop cluster setup for scalable storage and coordination
- Authored accompanying research paper (currently under review)

## Recognition

- Earned research funding from PIEAS
- Received Appreciation Certificate for Outstanding Final Year Project
- Supervised by Dr. Muhammad Imran (former CERN scientist, NCP) and Dr. Irfan Ul Haq (PIEAS)

**Period:** Jun 2023 – Jun 2024
