# Louis-Philip Marcoux

Software engineer focused on distributed systems, systems programming, and infrastructure.
I build things at the layer most people use as a black box — consensus algorithms, container runtimes, storage engines, ML platforms.

Founder of [Groupe Sentinella](https://groupesentinella.com).

---

## Featured Projects

### Distributed Systems & Storage

| Project | Stack | Description |
|---|---|---|
| [raft](https://github.com/louisphilipmarcoux/raft) | Rust | Distributed KV store with Raft consensus — custom LSM-tree, MVCC/OCC transactions, linearizable reads, joint consensus membership, chaos testing. 230+ tests. Published on crates.io. |
| [redis-zig](https://github.com/louisphilipmarcoux/redis-zig) | Zig | Redis server built from scratch — RESP2 protocol, 41+ commands, master-replica replication with PSYNC, pub/sub, streams, transactions, geospatial indexing, and ACL |

### Container Runtime & Infrastructure

| Project | Stack | Description |
|---|---|---|
| [vessel](https://github.com/louisphilipmarcoux/vessel) | Go | OCI-compatible container runtime — namespaces, cgroups v2, overlayfs, seccomp, bridge networking |
| [go-load-balancer](https://github.com/louisphilipmarcoux/go-load-balancer) | Go | Production-grade HTTP load balancer with health checks, Kubernetes manifests, and Terraform configs |

### ML Platform

| Project | Stack | Description |
|---|---|---|
| [giga-flow-mlops](https://github.com/louisphilipmarcoux/giga-flow-mlops) | Python, Kafka, MLflow | Production-grade MLOps platform — real-time multilingual sentiment analysis, 28-emotion detection, toxicity screening. 4 ML models (ModernBERT, RoBERTa, XLM-R), 14 Docker services, A/B testing, drift detection, auto-retraining, Redis caching, Grafana dashboards, Kubernetes-ready. [Docs ↗](https://louisphilipmarcoux.github.io/giga-flow-mlops/) |

### Parsers & Language Tooling

| Project | Stack | Description |
|---|---|---|
| [rill-json](https://github.com/louisphilipmarcoux/rill-json) | Rust | RFC 8259-compliant streaming JSON parser and serializer — 100% safe Rust,
