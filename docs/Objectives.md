Measurable Objectives

Environment Details
- OS: Windows 11
- Environment: Docker Compose local stack
- CVAT Commit SHA: d8193c584be9ce6cf9882dad06c0dd920cc0b9c5

---

Objective MO-1: Annotation Count Endpoint Latency

- What is measured: Response time of GET /api/test/tasks/<id>/annotation-counts/
- How: 5 sequential curl requests
- Target: Median latency <= 250ms
- Conditions: Local Docker stack, COCO dataset imported
- Exclusions: Cold start

Measurements
- Run 1: Pending
- Run 2: Pending
- Run 3: Pending
- Run 4: Pending
- Run 5: Pending
- Median: Pending
- Spread: Pending