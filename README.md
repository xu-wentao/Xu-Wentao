<div align="center">

# Hi, I'm Wentao Xu

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=21&duration=2600&pause=850&color=58A6FF&center=true&vCenter=true&repeat=true&width=860&height=90&lines=%24+whoami%3A+Wentao+Xu+%E2%80%94+AI+Infrastructure+Engineer;%24+contributing%3A+Kubernetes+%C2%B7+Volcano+%C2%B7+Prometheus+Operator;%24+mission%3A+Building+reliable+open-source+infrastructure)](https://git.io/typing-svg)

</div>

Cloud-native and AI infrastructure engineer working across **Kubernetes, heterogeneous accelerator scheduling, observability, distributed systems, and LLM infrastructure**.

I spend much of my engineering time studying production problems, turning them into reusable designs, and contributing the resulting improvements back to open-source communities.

## Open-source focus

- Kubernetes scheduling and resource management for AI workloads
- Dynamic Resource Allocation (DRA), GPU / NPU devices, and multi-tenant quota control
- Operators, controllers, observability, and production reliability
- Cloud-native database automation and disaster recovery
- Go-based infrastructure components and platform tooling

## Recent community contributions

### Volcano

- **[Merged] [Capacity plugin support for DRA](https://github.com/volcano-sh/volcano/pull/5058)**  
  Added queue-level quota management for Kubernetes Dynamic Resource Allocation, covering whole devices, consumable capacities, hierarchical queues, shared claims, tests, design documentation, and user guidance.

- **[In review] [Optimize PodGroup listing with FieldSelector](https://github.com/volcano-sh/volcano/pull/4876)**  
  Uses server-side custom-resource field selectors on Kubernetes 1.31+, while retaining a compatibility fallback for older clusters.

### Prometheus Operator

- **[In review] [Support basic authentication for Prometheus web servers](https://github.com/prometheus-operator/prometheus-operator/pull/7004)**  
  Extends the operator API and generated workloads to configure server-side basic authentication from Kubernetes Secrets, including authenticated probes.

### Apache ShardingSphere on Cloud

Contributed features and fixes across the operator and point-in-time recovery tooling, including:

- [AWS Aurora storage-node registration and lifecycle integration](https://github.com/apache/shardingsphere-on-cloud/pull/398)
- [Backup progress reporting for PITR workflows](https://github.com/apache/shardingsphere-on-cloud/pull/321)
- [Environment-file support for PITR agent commands](https://github.com/apache/shardingsphere-on-cloud/pull/319)
- [Backup metadata, PTRACK mode, and storage-node correctness fixes](https://github.com/apache/shardingsphere-on-cloud/pull/288)
- [Chaos-test environment and controller port-conflict fixes](https://github.com/apache/shardingsphere-on-cloud/pull/348)

### NVIDIA GPU Operator

- [Corrected Prometheus relabeling examples in GPU Operator values](https://github.com/NVIDIA/gpu-operator/pull/1157), aligning the configuration with the expected ServiceMonitor field names.

## What I care about

> Infrastructure should remain understandable and dependable, even when the systems running on it become increasingly complex.

I am particularly interested in work where scheduler design, Kubernetes APIs, accelerator topology, observability, and operational experience meet.

## Working stack

`Kubernetes` · `Go` · `DRA` · `Volcano` · `GPU / NPU` · `Prometheus` · `Grafana` · `Helm` · `containerd` · `Python` · `Rust` · `TypeScript`

---

中文简介：云原生与 AI 基础设施工程师，持续参与 Volcano、Prometheus Operator、Apache ShardingSphere on Cloud 等开源社区，关注 Kubernetes 调度、DRA、异构算力管理、可观测性以及大模型训练与推理基础设施。