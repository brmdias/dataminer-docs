---
uid: automatic_incident_tracking_benchmarks
---

# Automatic incident tracking benchmarks

## Specifications of the test server

- Intel Xeon E5-2620 v4
- 2 sockets
- 16GB RAM
- Cassandra (for alarm focus and the creation of alarms)
- Windows Server 2012 R2

## Benchmarks

| \# | Specification | Scope | Metric | Remarks | Configuration |
| -- | ------------- | ----- | ------ | ------- | ------------- |
| 1 | Create group with 2,000 base alarms | DMS | 68 s | Create 2,000 alarms on the same parameter (in a table) and wait until all these alarms are grouped. Alarms are only grouped after the focus score has been calculated. | No other tests running. |
| 2 | Clear group with 2,000 base alarms | DMS | 20 s | Clear all 2,000 base alarms from a group and wait until the group itself has been cleared. | No other tests running. |
