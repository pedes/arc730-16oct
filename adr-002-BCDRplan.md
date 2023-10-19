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
