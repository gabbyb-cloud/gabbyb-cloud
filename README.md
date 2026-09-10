# Gabby B

Software engineer focused on backend systems, platform engineering, and reliability.

I build backend services and reliability-focused infrastructure with an emphasis on failure handling, observability, recovery, and measurable system behavior. My projects explore how systems behave when dependencies fail, processes restart, workloads degrade, and services need to recover — not just when everything works normally.

**Currently seeking:** Backend Engineer, Platform Engineer, and Site Reliability Engineer opportunities.

## Featured Work

### [SRE Reliability Lab](https://github.com/gabbyb-cloud/sre-reliability-lab)

A Kubernetes-based reliability lab built around a containerized FastAPI service and designed to exercise the full monitoring, alerting, failure, and recovery lifecycle.

**Demonstrates:**
- Kubernetes deployment with kind and Helm
- Liveness and readiness probes
- Prometheus metrics and ServiceMonitor discovery
- Grafana visualization of a 99% availability SLO
- `HighErrorRate` alerting with Prometheus
- Controlled HTTP 500 failure injection
- Alert lifecycle from pending → firing → resolved
- Service recovery verification
- Operational runbook and blameless postmortem
- Terraform adoption and management of the Kubernetes namespace

### [Order Fulfillment Service](https://github.com/gabbyb-cloud/order-fulfillment-temporal)

A durable order-processing backend built with Temporal, FastAPI, PostgreSQL, Docker, and Python.

**Demonstrates:**
- Durable workflow orchestration
- Retryable and non-retryable failure handling
- Saga compensation
- Cancellation checkpoints
- Worker crash recovery
- Authenticated API boundaries
- Automated testing and GitHub Actions CI

### [Distributed Systems Performance Lab](https://github.com/gabbyb-cloud/distributed-systems-performance-lab)

A backend performance lab focused on measuring application behavior under controlled workload and dependency-failure conditions.

**Explores:**
- Database connection pooling
- Redis caching and fallback behavior
- Concurrency and request throughput
- Average, p95, and p99 latency
- Dependency failure behavior
- Observability and performance measurement

## Engineering Focus

`Backend Systems` · `Platform Engineering` · `Site Reliability Engineering` · `Distributed Systems` · `Observability` · `Infrastructure as Code`

## Technology

`Python` · `TypeScript` · `FastAPI` · `PostgreSQL` · `Redis` · `Temporal` · `Docker` · `Kubernetes` · `Helm` · `Terraform` · `Prometheus` · `Grafana` · `GitHub Actions` · `Linux`

## Engineering Principles

- Design for failure, not only the happy path
- Make system behavior observable and measurable
- Automate repeatable infrastructure and deployment work
- Test recovery paths as well as normal behavior
- Keep operational documentation close to the code
- Prefer measured results over vague performance claims
