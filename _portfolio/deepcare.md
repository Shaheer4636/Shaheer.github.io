---
title: "DeepCare — Multi-Disease Screening Platform"
excerpt: "A multi-disease AI screening platform for tabular and imaging data, deployed on Azure Web Apps with DNS, firewall, and CloudFront CDN.<br/>"
collection: portfolio
---

**DeepCare** is a multi-disease screening platform built with TensorFlow, scikit-learn, and Flask, deployed on Azure Web Apps.

## Overview

DeepCare provides per-disease AI workflows for both tabular and imaging data, with optional result storage. The platform is designed to make disease screening accessible through a web portal backed by trained ML models.

## Technical Stack

- **Frameworks:** TensorFlow, scikit-learn, Flask
- **Deployment:** Azure Web Apps with custom DNS configuration
- **Security:** Azure Firewall
- **CDN:** CloudFront (CDN) for low-latency global access

## Evaluation Metrics

Models were evaluated with:
- Accuracy, Precision, Recall, F1-score
- Confusion matrices for per-class performance analysis

## Architecture Highlights

- Modular per-disease workflow pipelines
- Supports both structured (tabular) and unstructured (imaging) input data
- Optional result persistence layer for longitudinal tracking
- Production-ready deployment with DNS, firewall rules, and CDN configuration

**Date:** March 2025
