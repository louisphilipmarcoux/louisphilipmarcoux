# Louis-Philip Marcoux

Software engineer focused on distributed systems, systems programming, and infrastructure.
I build things at the layer most people use as a black box — consensus algorithms, container runtimes, storage engines, ML platforms.

Founder of [Groupe Sentinella](https://groupesentinella.com).

---

## Flagship: A Three-System Production Stack

Three interconnected systems built sequentially at production quality — each complete within
its defined scope, each instrumenting or depending on the others.

| Project | Stack | Role in the stack |
|---|---|---|
| [vessel](https://github.com/louisphilipmarcoux/vessel) | Go | OCI container runtime — runs the raft cluster as isolated, resource-limited containers |
| [raft](https://github.com/louisphilipmarcoux/raft) | Rust | Distributed KV store — stores cluster state, emits OTel traces and Raft election metrics to lens |
| [lens](https://github.com/louisphilipmarcoux/lens) | Go + TypeScript + Python | Observability platform — ingests metrics, logs, and traces from vessel and raft |

vessel runs raft. raft emits telemetry. lens observes everything.

---

## Other Projects

### Distributed Systems & Storage

| Project | Stack | Description |
|---|---|---|
| [redis-zig](https://github.com/louisphilipmarcoux/redis-zig) | Zig | Redis server built from scratch — RESP2 protocol, 41+ commands, master-replica replication with PSYNC, pub/sub, streams, transactions, geospatial indexing, and ACL |

### ML Platform

| Project | Stack | Description |
|---|---|---|
| [giga-flow-mlops](https://github.com/louisphilipmarcoux/giga-flow-mlops) | Python, Kafka, MLflow | Production-grade MLOps platform — real-time multilingual sentiment analysis, 28-emotion detection, toxicity screening. 4 ML models (ModernBERT, RoBERTa, XLM-R), 14 Docker services, A/B testing, drift detection, auto-retraining, Redis caching, Grafana dashboards, Kubernetes-ready. [Docs ↗](https://louisphilipmarcoux.github.io/giga-flow-mlops/) |

### Parsers & Language Tooling

| Project | Stack | Description |
|---|---|---|
| [rill-json](https://github.com/louisphilipmarcoux/rill-json) | Rust | RFC 8259-compliant streaming JSON parser and serializer — 100% safe Rust, zero-allocation, published on crates.io |
| [shell-c](https://github.com/louisphilipmarcoux/shell-c) | C23 | POSIX-like shell — lexer, parser, AST, pipelines, job control, signal handling, trie-based tab completion, 50 integration tests |
| [pseudo-lisp-interpreter](https://github.com/louisphilipmarcoux/pseudo-lisp-interpreter) | Python | Lisp interpreter with lexer, parser, AST evaluator, macro expansion, static UML analysis, and call tracing |

---

## Tech

**Languages:** Rust · Zig · Go · C · Python · TypeScript  
**Distributed systems:** Raft consensus · LSM-tree · MVCC · RESP2 · gRPC · Protobuf  
**Observability:** eBPF · ClickHouse · PromQL · OpenTelemetry · Prometheus  
**ML/Data:** Kafka · MLflow · HuggingFace · Evidently AI · DVC · MinIO · Redis  
**Infrastructure:** Docker · Kubernetes · Terraform · GCP

---

[LinkedIn](https://www.linkedin.com/in/louis-philip-marcoux-b33269273) · [Groupe Sentinella](https://groupesentinella.com)
