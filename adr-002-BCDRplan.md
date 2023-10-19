# ADR 002: BCDR Plan

## Context

We need a plan otherwise without one we would need to improvise to solve a disaster or problem.

Objective: Keep the business operating as usual in case of a disaster, ensuring there's no downtime and services keep operating.

## Decision (Solution)

 HOW?

 Key Performance Indicator - Exercise: Find top 3 KPIs that need to be assured in the BCDR Plan

- Recovery Time Objective: Time to recover after a disruption MTD  Maximum Tolerable Downtime
  Alert: ??
  Response/Who's Responsible:
  Measure: 
- RPO Point Objective: If using databases, what data loss are we going to tolerate
  Data Backup Rate: Success/Failure  
- Incident Response Time: Recover + Time to fully resolve and notifiy end-users (perhaps includes postmortem actions), Audit reports
- Service Availability: Typically measured in nines, 99.90% - 99.999%
- Failure Rate: HTTP Requests, Out of 100 - 20 (4xx, 5xx), 20% Error Rate

 https://aws.amazon.com/blogs/publicsector/achieving-five-nines-cloud-justice-public-safety/

![image](https://www.altis-dxp.com/tachyon/2022/10/RTO-RPO.png?resize=1801%2C668&zoom=1)
 


# Business Continuity and Disaster Recovery (BCDR) Plan

## Table of Contents
- [1. Introduction](#1-introduction)
- [2. Key Performance Indicators (KPIs)](#2-key-performance-indicators-kpis)
- [3. Alerts](#3-alerts)
- [4. Monitoring Dashboards](#4-monitoring-dashboards)
- [5. Response Actions](#5-response-actions)

## 1. Introduction
This document outlines the Business Continuity and Disaster Recovery (BCDR) plan for [Your Company Name]. The purpose of this plan is to ensure the continuity of our services and minimize the impact of any unexpected disruptions.

## 2. Key Performance Indicators (KPIs)
The success of our BCDR plan will be evaluated based on the following Key Performance Indicators (KPIs):

### 2.1. Recovery Time Objective (RTO)
- Target RTO: [Define your target RTO in hours/minutes]

### 2.2. Recovery Point Objective (RPO)
- Target RPO: [Define your target RPO in hours/minutes]

### 2.3. Service Availability
- Target Service Availability: [Define your target service availability percentage]

### 2.4. Failure Rate
- Target Failure Rate: [Define your target failure rate]

## 3. Alerts
In order to achieve our BCDR objectives, we will implement alerting mechanisms to detect potential issues in real-time. These alerts will be based on predefined thresholds related to our KPIs.

- Alert 1: [Description of the first alert]
- Alert 2: [Description of the second alert]
- ...

## 4. Monitoring Dashboards
We will utilize monitoring dashboards to visualize the status of our systems and services. These dashboards will provide real-time and historical data related to the KPIs and other relevant metrics.

- [Monitoring Dashboard 1](URL): Description of the first dashboard.
- [Monitoring Dashboard 2](URL): Description of the second dashboard.
- ...

## 5. Response Actions
When alerts are triggered or our KPIs indicate a potential issue, the following response actions will be taken to ensure the BCDR plan is executed effectively:

### 5.1. Recovery Time Objective (RTO) Actions
- Action 1: [Description of the first action]
- Action 2: [Description of the second action]
- ...

### 5.2. Recovery Point Objective (RPO) Actions
- Action 1: [Description of the first action]
- Action 2: [Description of the second action]
- ...

### 5.3. Service Availability Actions
- Action 1: [Description of the first action]
- Action 2: [Description of the second action]
- ...

### 5.4. Failure Rate Actions
- Action 1: [Description of the first action]
- Action 2: [Description of the second action]
- ...

## Conclusion
This BCDR plan will be regularly reviewed, tested, and updated to ensure its effectiveness in maintaining business continuity and disaster recovery.

*Note: Replace placeholders such as "[Your Company Name]" and "[Define your target...]" with specific information relevant to your organization and its BCDR plan.*



## Status

Proposed

## Consequences

[Describe the consequences, both positive and negative, of the decision, including any risks or dependencies.]

## Related documents

[List any related documents, such as requirements or design documents, that influenced the decision.]

### References
- https://github.com/joelparkerhenderson/architecture-decision-record
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/metrics-monitors-alerts/index.md
- https://github.com/pmerson/ADR-template
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/timestamp-format/index.md
- https://cloud.google.com/architecture/architecture-decision-records
