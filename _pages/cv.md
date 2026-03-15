---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **B.S. Computer and Information Sciences** — PIEAS, Islamabad, Pakistan
  Sep 2020 – Jun 2024 | CGPA: 3.48/4.0
  Honors: Distinction in 4 subjects | Appreciation Certificate (Outstanding FYP)

Research Experience
======
* **Research Intern** — National Centre for Physics (NCP – CoE Aitec), Islamabad
  Jun 2023 – Sept 2023
  * Prototyped a Kubernetes-based multi-tenant ML platform using Kubeflow on on-premise physical servers with LDAP-backed authentication and resource quota controls (CPU/memory).
  * Deployed a distributed big-data processing stack using Apache Hadoop (HDFS, YARN), HBase, and ZooKeeper.
  * Assisted in cluster setup, service configuration, and operational validation in a shared research computing environment.
  * Supervised by Dr. Muhammad Imran (former CERN scientist).

Work Experience
======
* **Cloud and DevOps Engineer** — AppLab Qatar, Islamabad *(Oct 2025 – Present)*
  * Built endpoint heartbeats with AWS CloudWatch Synthetics to meet 99.99% SLA, tracking p95/p99 latency with CloudWatch/SNS alerts that reduced MTTR.
  * Developed a reporting pipeline from canary HTML → S3 → Lambda → ECR container (wkhtmltopdf) → timestamped PDF, triggered by EventBridge, secured with IAM least privilege, KMS, and S3 lifecycle.
  * Released Terraform-based infrastructure with CI/CD in Azure DevOps and GitHub Actions, used env-scoped tfvars, produced proactive SLA-breach alerts and ~40% less manual reporting.

* **DevOps Engineer** — [Priv Inc.](https://drive.google.com/file/d/1PUew2dQhjoTGv6m7fjJSUG2gRx5gH2XC/view), Dallas TX (Remote) *(Apr 2024 – Oct 2025)*
  * Delivered reliable AWS infrastructure across Kubernetes, databases, and Elasticsearch with centralized monitoring sustaining 99.9%+ uptime.
  * Established disaster-recovery runbooks and codified the stack in Terraform, enabling ≤1-hour RTO and ≤15-minute RPO.

* **Lead Instructor / Teaching Assistant** — [Primus Learning](https://drive.google.com/file/d/1zM_2k1ZWaLyvjQhLqScKt3U0dh6mFG4R/view), Dallas TX (Remote) *(Feb 2025 – May 2025)*
  * Delivered 120 hours of live instruction to 25 learners covering Python, OOP, pytest, CI/CD, containerization, and SDLC lifecycle.
  * Designed weekly objectives, hands-on labs, graded assignments, and supervised a capstone project incorporating GitHub Actions CI pipeline.

Skills
======
* **Languages:** Python, Golang, SQL, HTML, CSS
* **Cloud & Infrastructure:** AWS (CloudWatch, Lambda, EKS, S3, IAM, ECR, EventBridge, SNS, KMS), Azure (Web Apps, DevOps, DNS, Firewall), Terraform
* **Container & Orchestration:** Kubernetes, Kubeflow, Docker, Helm
* **Databases:** MySQL, PostgreSQL, DynamoDB, Elasticsearch, HBase
* **Big Data:** Apache Hadoop (HDFS, YARN), ZooKeeper
* **ML/DL Frameworks:** TensorFlow, scikit-learn, PyTorch
* **Developer Tools:** VS Code, GitHub, GitLab, Jira, Google Colab, Jupyter

Test Scores
======
* **GRE General Test** (Jul 24, 2025): Verbal Reasoning 165 (95th percentile) | Quantitative Reasoning 163 (60th percentile) | Analytical Writing 4.0 (63rd percentile)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and Leadership
======
* **Cloud Captain** — AWS Cloud Club PIEAS, PIEAS (Jan 2022 – Jan 2023)
  * Organized 4 campus events on AWS technologies; grew student and faculty participation; participated in global AWS online sessions.
  * Recognized by AWS with an [official experience letter](https://drive.google.com/file/d/1E0Q13bcEZTLVbNO2te4i9Bzk6V6k2yWv/view).

* **Chairperson** — IEEE CS Chapter PIEAS (Sept 2022 – Sept 2023)
  * Led the Computer Science chapter of the IEEE PIEAS Student Branch; organized technical events, workshops, and community initiatives.
  * Received [IEEE Letter of Appreciation](https://drive.google.com/file/d/15KgmttvxMtfzPMsO5thpGPh0Tmp7wNFF/view?usp=sharing) for outstanding service (June 2024).
